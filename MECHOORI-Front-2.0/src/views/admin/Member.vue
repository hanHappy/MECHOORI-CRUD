<script setup>
</script>

<template>
    <main class="admin-main">
        <!-- 검색바 -->
        <div class="search-input-wrap">
            <input type="text" class="input placeholder-effect" placeholder="회원 검색">
            <button class="button icon icon-search"></button>
        </div>

        <section class="list-section">
            <h1 class="d-none">회원 리스트</h1>
            <nav class="column-wrap">
                <ul>
                    <li>ID</li>
                    <li>ROLE ID</li>
                    <li>이름</li>
                    <li>닉네임</li>
                    <li>이메일</li>
                    <li>프사</li>
                    <li>등록일</li>
                    <li>로그인 타입 ID</li>
                    <li><router-link to="member/add" class="button button-13">＋</router-link></li>
                </ul>
            </nav>
            <div class="list">
                <section class="data content">
                    <p></p>
                    <p></p>
                    <p></p>
                    <p></p>
                    <p></p>
                    <p></p>
                    <p></p>
                    <p></p>
                    <div class="btns-wrap">
                        <router-link to="member/edit" class="button button-14 btn-edit">EDIT</router-link>
                        <button class="button button-14 btn-delete">DEL</button>
                    </div>
                </section>
            </div>
        </section>
    </main>
</template>

<style scoped>
@import url(@/assets/css/admin/restaurant.css);
</style>
