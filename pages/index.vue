<template>
    <section class="message">
        <table class="message__box">
            <tr class="message__header--row">
                <th class="message__header">
                    ホーム
                </th>
            </tr>
            <tr class="message__item">
                <td class="message__data">
                    <div class="message__item--box">
                        <span class="message__item--name">
                            ユーザーネーム
                        </span>
                        <div>
                            <img class="message__item--img" src="~/assets/img/heart.png">
                            <span>
                                0
                            </span>
                        </div>
                        <div>
                            <img class="message__item--img" src="~/assets/img/cross.png">
                        </div>
                        <div>
                            <NuxtLink :to="`/`">
                                <img class="message__item--img" src="~/assets/img/detail.png">
                            </NuxtLink>
                        </div>
                    </div>
                    testtest
                </td>
            </tr>
        </table>
    </section>
</template>

<style scoped>
@import '@/assets/css/message.css';
</style>