<template>
  <div class="footer">
    <div class="container-lg text-center text-sm-start">
      <div class="row footer__items">
        <div class="col-12 col-sm-6 col-lg-3 footer__items-block">
          <div>Довідка для покупців</div>
          <div>Отримати підтримку</div>
          <div>Як купувати</div>
          <div>Як залишити корисний відгук</div>
          <div>Програма Захисту Покупців</div>
          <div>Рекомендації з безпечних покупок</div>
        </div>
        <div class="col-12 col-sm-6 col-lg-3 footer__items-block">
          <div>Довідка для продавців</div>
          <div>Як почати продавати</div>
          <div>Тарифи</div>
          <div>Угода користувача</div>
          <div>Політика конфіденційності</div>
          <div>Правила користування порталом</div>
          <div>Бонусна програма</div>
        </div>
        <div class="col-12 col-sm-6 col-lg-3 footer__items-block">
          <div>Про нас</div>
          <div>Довідка та FAQ</div>
          <div>Захист легальності контенту</div>
          <div>Адміністрація</div>
          <div>Вакансії</div>
        </div>
        <div class="col-12 col-sm-6 col-lg-3 footer__items-block">
          <div>Мобільний додаток</div>
          <img class="footer__items-block-item" :src="require('@/assets/icons/google-play.svg')"/>
        </div>
      </div>
      <Divider/>
      <div class="row">
        <div class="col-lg-12 footer__copyright">
          © 2022 Monvalise
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Divider from "@/components/Divider";

export default {
  name: "Footer",
  components: {Divider}
}
</script>

<style scoped>

</style>