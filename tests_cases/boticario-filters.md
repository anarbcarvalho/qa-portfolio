### Test Case 1: Size Filter in Search - "Sabonete"

**Prerequisites:**  
- Internet access  
- Access the website: https://www.oboticario.pt/

**Test Data:**  
- Search term: "Sabonete"  
- Filter option: "250ml"

**Test Steps:**  
1. Access the URL: https://www.oboticario.pt/
2. Click on the magnifying glass icon (search)  
3. Type "Sabonete" in the search bar ("O que procuras?")  
4. Click on "Ver todos os resultados"  
5. Click the "Filtros" button  
6. Select the "Tamanho" filter  
7. Choose the option "250ml"  
8. Click "Ver Resultados"

**Expected Result:**  
- The result list displays only products with the size 250ml visible in their descriptions or details

**Actual Result:**  
- The result list displays only products with the size "250ml"

**Test Result:**  
- Pass✅

---

### Test Case 2: Apply Multiple Filters in Search - Sabonete

**Prerequisites:**  
- Internet access  
- Access the website: https://www.oboticario.pt/

**Test Data:**  
- Any product available in an active subcategory  
- "Preço" filter: 0.00€ - 10.00€  
- "Tamanho" filter: 250ml  
- "Marca" filter: Malbec

**Test Steps:**  
1. Click on the search icon  
2. Type "Sabonete" in the search bar ("O que procuras?")  
3. Click the "Ver todos os resultados" button  
4. Click the "Filtros" button  
5. Select the "Preço" filter  
6. Drag the right handle to the value "10" on the price slider  
7. Select the "Tamanho" filter  
8. Choose the option "250ml"  
9. Select the "Marca" filter  
10. Choose the brand "Malbec"  
11. Click the "Ver Resultados" button  
12. Verify that the displayed products comply with the selected filters

**Expected Result:**  
- The result list should display only products classified as "Sabonete" that meet the applied filters:  
  - Price between 0.00€ and 10.00€  
  - Size 250ml  
  - Brand Malbec

**Actual Result:**  
- The displayed products are soaps with price ≤ 10.00€, size 250ml, and brand Malbec, according to the applied filters

**Test Result:**  
- Pass✅ 

---

### Test Case 3: Price Filter in Search - Perfume

**Prerequisites:**  
- Internet access  
- Access the website: https://www.oboticario.pt/

**Test Data:**  
- Search term: "perfume"  
- Price filter: 0.00€ to 20.00€

**Test Steps:**  
1. Click on the magnifying glass icon (search)  
2. Type "perfume" in the search bar ("O que procuras?")  
3. Click on "Ver todos os resultados"  
4. Click the "Filtros" button  
5. Select the "Preço" filter  
6. Drag the right handle to the value "20" on the price slider  
7. Click "Ver Resultados"

**Expected Result:**  
- The result list displays only perfume products priced between 0.00€ and 20.00€

**Actual Result:**  
- The result list contains products priced up to 20.00€, but not all are perfumes

**Test Result:**  
- Not Pass❌

---