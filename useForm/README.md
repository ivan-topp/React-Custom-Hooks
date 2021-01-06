# useForm Hook

Ejemplo de uso:

```
    const [ values, handleInputChange, reset ] = useForm({
        name: "example",
        email: "example@dominio.com"
    });

```

En React:

```
    <input 
        type="text"
        name="name"
        placeholder="Name"
        autoComplete="off"
        value={ name }
        onChange={ handleInputChange }
    />
    <input 
        type="text"
        name="email"
        placeholder="Email"
        autoComplete="off"
        value={ email }
        onChange={ handleInputChange }
    />
```