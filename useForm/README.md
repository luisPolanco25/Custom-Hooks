# useForm Hook

Example of its use:
```
    const initialForm = {
        name: '',
        age: 0,
        email: '',
    }
    const [formValues, handleInputChange, reset] = useForm(initialForm); 
```