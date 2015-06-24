---
title: Markdown Export
author: Stephen Barr
date: 2015-01-30
mathjax: on
---


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam
non est in neque luctus eleifend. Sed tincidunt vestibulum
facilisis. Aenean ut pulvinar massa.

Some math inline $x^{2}$

$$
\begin{equation}
y^{3}
\end{equation}
$$

```haskell
    newtype MonadMonoid m a = MonadMonoid { unMonad :: a -> m a }
    
    instance Monad m => Monoid (MonadMonoid m a) where
      mempty = MonadMonoid return
      mappend f g = MonadMonoid (f >=> g)
```

done
