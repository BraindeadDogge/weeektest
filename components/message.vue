<template>
  <div>
    <a disabled class="notif"><span class="num">2</span></a>
  </div>
</template>

<style>
a.notif {
  position: relative;
  display: block;
  height: 30px;
  width: 30px;
  background: url('/message.svg');
  background-size: contain;
  text-decoration: none;
}
.num {
  position: absolute;
  font-size: 9px;
  font-weight: bold;
  line-height: 11px;
  letter-spacing: .5px;
  display: flex;
  align-items: center;
  text-align: center;
  right: -3px;
  top: -3px;
  color: #fff;
  padding: 1.5px;
  background-color: #36C275;
  border-radius: 4px;
  transform: scale(1.5);
}
</style>
