# merge_sort

[16,21,11,8,12,22] -> Merge Sort
Q1-)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.


1.adım:
	ilk olarak arrayimizi ikiye böleceğiz daha sonra tek bir elemana indirgeyene kadar işleme devam edeceğiz.
	[16,21,11,8,12,22] --> [16,21,11]   [8,12,22]
2.adım: 
	Bu adımda 3 elemanlı iki tane arrayimiz olduğu için her iki arrayi de 2 elemanlı ve 1 elemanlı olmak üzere ayıracağız.
	[16,21,11] --> [16,21] [11]      [8,12,22] --> [8,12] [22]
3.adım:
	Bu adımda ise arrayi tek elemana indergemiş olacağız.
	[16,21] [11] --> [16] [21] [11]       [8,12] [22]  --> [8] [12] [22]
4.adım: 
	Bu aşamada artık merge işlemine başlamış olacağız. İlk olarak 3.adımda parçalamış olduğumuz iki tane 2 elemanlı arrayi kontrol edip merge edeceğiz.
	[16] [21] [11]  --> [16,21] [11]      [8] [12] [22]  -->  [8,12] [22]
5.adım:
	Bu adımda ise merge edilmiş iki tane 2 elemanlı arrayi diğer elemanı da katarak üç elemanlı merge gerçekleşmiş olacak.
	[16,21] [11] --> [11,16,21]           [8,12] [22]  --> [8,12,22]
6.adım:
	Son adımda ise başlangıçta ikiye bölmüş olduğumuz arrayi tekrar birleştiriyoruz ve merge sort algoritmasına göre sorting işlemini tamamlamış oluyoruz.
	[11,16,21]   [8,12,22]   --> [8,11,12,16,21,22]
	
	
Q2-)Big-O gösterimini yazınız.
	Big-O gösterimi : O(nlogn)
