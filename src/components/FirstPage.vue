
<template>
  <div>
    <main-header></main-header>
    <main>
      <div class="content_container">
        <div class="main_menu">
          <main-menu></main-menu>
        </div>
        <div class="messageArea_container">
             <message-box></message-box>
          <message-list></message-list>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Menu from "@/components/Menu";
import MessageBox from "@/components/MessageBox";
import MessageList from "@/components/MessageList";
export default {
  name: "FirstPage",
  props: {
    msg: String,
  },
  components: {
    "main-header": Header,
    "main-menu": Menu,
    "message-box": MessageBox,
    "message-list": MessageList
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
