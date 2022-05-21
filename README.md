# kotlin Practice programs

<B>Bubble Sort<br><B>
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

 

2) Searching Any Elements 
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
  
