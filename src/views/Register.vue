<template>
  <div class="register">
    <sidebar-menu :menu="menu" />
    <register />
  </div>
</template>
<script>
import register from "@/components/CreateAccountComponent";
export default {
  components: {
    register,
  },
  data() {
    return {
      menu: [
        {
          header: true,
          title: "Menu",
          hiddenOnCollapse: true,
        },
        {
          href: "/form",
          title: "Envoyer un fichier",
          icon: "fa fa-user",
        },
        {
          href: "/profil",
          title: "Mon profil",
          icon: "fa fa-chart-area",
        },
      ],
    };
  },
};
</script>

<style>
.v-sidebar-menu {
}
.v-sidebar-menu.vsm_expanded {
}
.v-sidebar-menu.vsm_collapsed {
}
.v-sidebar-menu.vsm_rtl {
}
.v-sidebar-menu .vsm--item {
}
.v-sidebar-menu .vsm--item.vsm--item_open {
}
.v-sidebar-menu .vsm--link {
}
.v-sidebar-menu .vsm--link.vsm--link_active {
}
.v-sidebar-menu .vsm--link.vsm--link_exact-active {
}
.v-sidebar-menu .vsm--link.vsm--link_mobile-item {
}
.v-sidebar-menu .vsm--link.vsm--link_level-[n] {
}
.v-sidebar-menu .vsm--link.vsm--link_disabled {
}
.v-sidebar-menu .vsm--title {
}
.v-sidebar-menu .vsm--icon {
}
.v-sidebar-menu .vsm--arrow {
}
.v-sidebar-menu .vsm--arrow.vsm--arrow_open {
}
.v-sidebar-menu .vsm--badge {
}
.v-sidebar-menu .vsm--header {
}
.v-sidebar-menu .vsm--list {
}
.v-sidebar-menu .vsm--dropdown > .vsm--list {
}
.v-sidebar-menu .vsm--mobile-item {
}
.v-sidebar-menu .vsm--mobile-bg {
}
.v-sidebar-menu .vsm--toggle-btn {
}
</style>