# kotlin Practice programs

1.<B>Bubble Sort<br><B>
  fun main() { 

  var arrayOfElements=intArrayOf(1,12,4,3,20,6) 

var x=bubbleSort(arrayOfElements) 

for(i in 0 until arrayOfElements.size){ 

     println(arrayOfElements[i]) 

} 

} 

  

fun bubbleSort(elements:IntArray){ 

    var length=elements.size 

    var temp=0 

    for(i in 0 until length){ 

        for(j in 1 until length-1){ 

            if(elements[j-1]>elements[j]){ 

                temp=elements[j-1] 

                elements[j-1]=elements[j] 

                elements[j]=temp 

            } 

        } 

    } 

} 

 

2) Searching Any Elements<br>
fun main() { 

  var arrayOfElements=intArrayOf(1,12,4,3,20,6) 

  serachElements(arrayOfElements,245) 

} 

 

fun serachElements(elements:IntArray,searchItem:Int){ 

   var lenght=elements.size 

   var isFound=false 

     

        for(i in 0 until lenght) 

        { 

            if(elements[i] == searchItem){ 

                isFound=true 

            } 

            else{ 

               // isFound=false 

            } 

        } 

         

        if(isFound){ 

            print("element is found....") 

        } 

        else{ 

            print("element is not found.......") 

        } 

        } 
  
 <b> String each word Reverse</b>
  <code><pre>fun stringReverse(sentences:String){ 
    var sentences="My is neeraj kumar keshri" 
        var splitedSentences=sentences.split(" ") 
        for(i in splitedSentences.indices){ 
            println(splitedSentences[i].reversed()) 
        } 
  }</pre> </code>
  
  
  <b>Sum of even numbers in array </b>
  <code>fun main() {<br>
  var arrayOfElements=intArrayOf(1,12,4,3,20,6,4,5)<br>
  addEvenPostionElements(arrayOfElements)<br>
}<br>


fun addEvenPostionElements(arr:IntArray)<br>
{<br>
    var sum=0<br>
    for(i in 0 until arr.size){<br>
        if(arr[i]%2==0){<br>
           sum =sum+arr[i] <br>
        }<br>
        
    }<br>
   print(sum)<br>
}<br>
