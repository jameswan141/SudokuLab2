public boolean ContainsZero() {
 	 * @return - return 'true' if iValue exists in arr
 	 */
 	public boolean doesElementExist(int[] arr, int iValue) {
 		// TODO: Return 'true' if iValue is found in arr

 		boolean doesElementExist = false;
 		for (int i = 0; i < arr.length; i++) {
 @@ -100,8 +99,6 @@ public boolean doesElementExist(int[] arr, int iValue) {
 	 */
 	public int[] getColumn(int iCol) {

 		// TODO: Return a given column from LatinSquare

 		int[] Col = new int[this.LatinSquare.length];

 		for (int row = 0; row < this.LatinSquare.length; row++) {
 @@ -138,8 +135,6 @@ public boolean doesElementExist(int[] arr, int iValue) {
 	 * @return one dimensional array of the given row
 	 */
 	public int[] getRow(int iRow) {
 		// TODO: Return a given row from LatinSquare

 		int[] Row = new int[this.LatinSquare.length];

 		Row = this.LatinSquare[iRow];
 @@ -159,7 +154,6 @@ public boolean doesElementExist(int[] arr, int iValue) {
 	 * @return return 'true' if every element from source array is in target array
 	 */
 	public boolean hasAllValues(int[] arr1, int[] arr2) {
 		// TODO: Return 'true' if every element from arr2 is in arr1

 		boolean hasAllValues = true;
 		for (int j = 0; j < arr2.length; j++) {
 @@ -193,8 +187,6 @@ public boolean hasAllValues(int[] arr1, int[] arr2) {
 	 */
 	public boolean hasDuplicates(int[] arr) {

 		// TODO: Return 'true' if any element in arr is duplicate

 		boolean hasDuplicates = false;
 		int[] sortedArray = Arrays.copyOf(arr, arr.length);
 		Arrays.sort(sortedArray);
 @@ -220,13 +212,7 @@ public boolean hasDuplicates(int[] arr) {
 	public boolean isLatinSquare() {

 		boolean isLatinSquare = true;
 		// TODO: Return 'true' if...
 		// Each row and column doesn't contain duplicates
 		// If each element in the first row is found in every other row
 		// If each element in the first coumn is found in every other column

 		// Check to see if the any row or column has duplicates. If they do, return
 		// false;
 		for (int i = 0; i < LatinSquare.length; i++) {
 			if (hasDuplicates(getRow(i)))
 				return false;
