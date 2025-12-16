### Test Case 6: Sopping Cart Validation after Adding a Product

**Prerequisites:**  
- Internet access  
- Access to the website: https://www.oboticario.pt/

**Test Data:**  
- Any product available in an active subcategory

**Test Steps:**  
1. Click on the menu icon  
2. Select the "Produtos" tab  
3. Choose a category  
4. Choose a subcategory  
5. Select a random product  
6. Click "Adicionar"  
7. Check if the "Carrinho" side panel opens  
8. Verify that the selected product appears in the cart.
9. Verify that the quantity displayed matches the selected quantity

**Expected Result:**  
- The cart should display the selected product and the correct quantity

**Actual Result:**  
- The cart displays the selected product and the correct quantity

**Test Result:**  
- Pass✅

---

### Test Case 7: Verify "Remover" Button Functionality in the cart

**Prerequisites:**  
- Internet access  
- Access the website: https://www.oboticario.pt/

**Test Data:**  
- Any product available in an active subcategory

**Test Steps:**  
1. Click on the menu icon  
2. Select the "Produtos" tab  
3. Choose a category  
4. Choose a subcategory  
5. Select a random product  
6. Click "Adicionar"  
7. Check if the "Carrinho" side panel opens  
8. Verify that the selected product appears in the cart  
9. Click the "Remover" button  
10. Confirm that the product is removed from the cart  
11. Verify that the message "O carrinho está vazio" is displayed

**Expected Result:**  
- The "Remover" button should remove the selected product from the cart  
- The message "O carrinho está vazio" should be displayed

**Actual Result:**  
- The "Remover" button removed the selected product  
- The message "O carrinho está vazio" is displayed

**Test Result:**  
- Pass✅

---

### Test Case 8: Modify Product Quantity in the Cart

**Prerequisites:**  
- Internet access  
- Access the website: https://www.oboticario.pt/

**Test Data:**  
- Any product available in an active subcategory

**Test Steps:**  
1. Click on the menu icon  
2. Select the "Produtos" tab  
3. Choose a category  
4. Choose a subcategory  
5. Select a random product  
6. Click "Adicionar"  
7. Check if the "Carrinho" side panel opens  
8. Verify that the selected product appears in the cart  
9. Click the "+" button to increase the product quantity  
10. Verify that the displayed quantity is updated  
11. Confirm that the total price corresponds to two units  
12. Click the "-" button to decrease the product quantity  
13. Verify that the displayed quantity is updated  
14. Confirm that the total price returns to the value of one unit

**Expected Result:**  
- The "+" and "-" buttons in the cart should increase and decrease the product quantity accordingly

**Actual Result:**  
- The "+" and "-" buttons correctly updated the product quantity

**Test Result:**  
- Pass✅