# JEMT-Product-Card

Este es un paquete de pruebas de despliegue en npm

### José Eduardo Malfavón Talavera


## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'jemt-product-card';
```

```
<ProductCard
    product={product}
    initialValues={{ count: 4, maxCount: 10 }}
>
    {({ reset, count, increaseBy, isMaxCountReached }) => (
        <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
        </>
    )}
</ProductCard>
```