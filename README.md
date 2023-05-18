# AJY7-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Axel Jiménez

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'ajy7-product-card';
```

```

<ProductCard
        product={product}
        initialValues={{ count: 6, maxCount: 10 }}
      >
        {({ reset, count, increaseBy, isMaxCountReached, maxCount }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
</ProductCard>

```
