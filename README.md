# DSA_Codes
class Heap:
def__init__(self):
self.arr=[]

def heapify(self,n,i):
    largest = i
    left=2*i+1
    right=2*i+2
    if left<n & self.arr[left]>self.arr[largest]:
        largest=left
    if right<n & self.arr[right]>self.arr[largest]:
        largest=right

    if largest!=i:
        self.arr[i],self.srr[largest]=self.srr[largest],sef.arr[i]
def build_max_heap(self):
    n=len(self.arr)
    for i in range(n//2-1,-1,-1)
    self.heapify(n,i)
    
def heapSort(self):
    n=len(self.arr)

    self.build_max_heap()

    for i in range(n-1,0,-1):
        self.arr[0],self.arr[i]=self.arr[i],self.arr[0]
        self.heapify(i,0)

def display(self)
 for i in range (len(self.arr)):
    print(self.arr[i],end="")
    print()

    if__name__=="__main__":
        heap=Heap()
        n=int(input("Enter number of elements:"))
        print("Enter the elements:")
        for_in range(n):
            element = int(input())
            heap.arr.append(element)
    print("Array before sorting:")
        heap.display()
        heap.heapSort()
            print("Array after sorting:")
        heap.display()    
        
