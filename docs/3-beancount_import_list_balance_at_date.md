# Beancount Import List Balance At Date

[_Documentation generated by Documatic_](https://www.documatic.com)

<!---Documatic-section-Codebase Structure-start--->
## Codebase Structure

<!---Documatic-block-system_architecture-start--->
```mermaid
None
```
<!---Documatic-block-system_architecture-end--->

# #
<!---Documatic-section-Codebase Structure-end--->

<!---Documatic-section-beancount_import.list_balance_at_date.get_digits-start--->
## beancount_import.list_balance_at_date.get_digits

<!---Documatic-section-get_digits-start--->
<!---Documatic-block-beancount_import.list_balance_at_date.get_digits-start--->
<details>
	<summary><code>beancount_import.list_balance_at_date.get_digits</code> code snippet</summary>

```python
def get_digits(x):
    s = str(x)
    k = s.find('.')
    if k == -1:
        return 0
    return len(s) - k - 1
```
</details>
<!---Documatic-block-beancount_import.list_balance_at_date.get_digits-end--->
<!---Documatic-section-get_digits-end--->

# #
<!---Documatic-section-beancount_import.list_balance_at_date.get_digits-end--->

[_Documentation generated by Documatic_](https://www.documatic.com)