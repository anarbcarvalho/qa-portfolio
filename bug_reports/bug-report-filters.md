### Bug Report 1: Incorrect Product Filtering by Price - Perfume Search

**Bug ID:** BR-001  
**Reported By:** Ana Carvalho  
**Severity:** Medium  
**Priority:** Low  

**Environment:**  
- Website: https://www.oboticario.pt/  
- Browser: Chrome (latest)  
- Device: Desktop  

**Description:**  
When applying the price filter (0.00€ - 20.00€) in the search results for "Perfume" the list includes products that are not perfumes, even though they fall within the selected price range.

**Steps to Reproduce:**  
1. Click on the magnifying glass icon (search)  
2. Type "perfume" in the search bar ("O que procuras?")  
3. Click on "Ver todos os Resultados"  
4. Click the "Filtros" button  
5. Select the "Preço" filter  
6. Drag the right handle to the value "20" on the price slider  
7. Click "Ver Resultados"  
8. Observe that some products displayed are not perfumes

**Expected Result:**  
- Only perfume products priced between 0.00€ and 20.00€ should be displayed

**Actual Result:**  
- The result list contains products priced up to 20.00€, but not all are perfumes

**Attachments / Screenshots:**  
- Not available (detailed description provided)

**Status:**  
- Open / Needs Investigation
