# kotlin Practice programs

<B>Bubble Sort<B>
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
