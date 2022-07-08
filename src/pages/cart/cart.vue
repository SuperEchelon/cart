<template>
    <div class="topline">
        <topline>
            <template #headline>
                <nav class="breadcrumbs">
                    <ul class="breadcrumbs__list">
                        <li class="breadcrumbs__item">
                            <a href="#" class="breadcrumbs__link">Главная</a>
                        </li>
                        <li class="breadcrumbs__item breadcrumbs__item--active">
                            <a href="#" class="breadcrumbs__link">Корзина</a>
                        </li>
                    </ul>
                </nav>
            </template>
            <template #content>
                <h2 class="cart__name">КОРЗИНА</h2>
            </template>
            <template #selected__content>
                <h2 class="selected">Выделено</h2>
            </template>
        </topline>
    </div>
</template>

<script>
import { topline } from '../../components/topline'
export default {
  name: 'cart',
  components: {
    topline
  }
}
</script>

<style lang="scss" src="./cart.scss" scoped></style>
