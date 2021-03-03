# BeautifulLanguageFeatures

# Function/method Arguments
1. Private argument that is not accessible outside of method and can only be accessible from the recursive call in function
   ```fun foo(a: Int, private b: Int) { foo(1,2) // valid }```
   ``` foo(1,3) // invalid ```
