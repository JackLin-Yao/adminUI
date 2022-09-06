<script setup></script>

<template>
  <div class="app-header">
    <div class="app-header-left">
      <span class="app-icon"></span>
      <p class="app-name">Portfolio</p>
      <div class="search-wrapper">
        <input class="search-input" type="text" placeholder="Search" />
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="20"
          height="20"
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          class="feather feather-search"
          viewBox="0 0 24 24"
        >
          <defs></defs>
          <circle cx="11" cy="11" r="8"></circle>
          <path d="M21 21l-4.35-4.35"></path>
        </svg>
      </div>
    </div>
    <div class="app-header-right">
      <button class="mode-switch" title="Switch Theme">
        <svg
          class="moon"
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <defs></defs>
          <path d="M21 12.79A9 9 0 1111.21 3 7 7 0 0021 12.79z"></path>
        </svg>
      </button>
      <button class="add-btn" title="Add New Project">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="16"
          height="16"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="3"
          stroke-linecap="round"
          stroke-linejoin="round"
          class="btn-icon feather feather-plus"
        >
          <line x1="12" y1="5" x2="12" y2="19" />
          <line x1="5" y1="12" x2="19" y2="12" />
        </svg>
      </button>
      <button class="notification-btn">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
          class="feather feather-bell"
        >
          <path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9" />
          <path d="M13.73 21a2 2 0 0 1-3.46 0" />
        </svg>
      </button>
      <button class="profile-btn">
        <img src="../../assets/logo.png" />
        <span>JackLin-Yao</span>
      </button>
    </div>
    <button class="messages-btn">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="20"
        height="20"
        viewBox="0 0 24 24"
        fill="none"
        stroke="currentColor"
        stroke-width="2"
        stroke-linecap="round"
        stroke-linejoin="round"
        class="feather feather-message-circle"
      >
        <path
          d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"
        />
      </svg>
    </button>
  </div>
</template>

<style scoped lang="scss">
.app-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  padding: 16px 24px;
  position: relative;
  &-left,
  &-right {
    display: flex;
    align-items: center;
  }

  &-left {
    flex-grow: 1;
  }

  &-right button {
    margin-left: 10px;
  }
}

.app-icon {
  width: 26px;
  height: 2px;
  border-radius: 4px;
  background-color: var(--main-color);
  position: relative;

  &:before,
  &:after {
    content: '';
    position: absolute;
    width: 12px;
    height: 2px;
    border-radius: 4px;
    background-color: var(--main-color);
    left: 50%;
    transform: translatex(-50%);
  }

  &:before {
    top: -6px;
  }
  &:after {
    bottom: -6px;
  }
}

.app-name {
  color: var(--main-color);
  margin: 0;
  font-size: 20px;
  line-height: 24px;
  font-weight: 700;
  margin: 0 32px;
}
.profile-btn {
  padding: 0;
  border: 0;
  background-color: transparent;
  display: flex;
  align-items: center;
  padding-left: 12px;
  border-left: 2px solid #ddd;

  img {
    width: 32px;
    height: 32px;
    object-fit: cover;
    border-radius: 50%;
    margin-right: 4px;
  }
}

.mode-switch {
  background-color: transparent;
  border: none;
  padding: 0;
  color: var(--main-color);
  display: flex;
  justify-content: center;
  align-items: center;
}

.search-wrapper {
  border-radius: 20px;
  background-color: var(--search-area-bg);
  padding-right: 12px;
  height: 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  max-width: 480px;
  color: var(--light-font);
  box-shadow: 0 2px 6px 0 rgba(136, 148, 171, 0.2),
    0 24px 20px -24px rgba(71, 82, 107, 0.1);
  overflow: hidden;

  .dark & {
    box-shadow: none;
  }
}

.search-input {
  border: none;
  flex: 1;
  outline: none;
  height: 100%;
  padding: 0 20px;
  font-size: 16px;
  background-color: var(--search-area-bg);
  color: var(--main-color);

  &:placeholder {
    color: var(--main-color);
    opacity: 0.6;
  }
}

.add-btn {
  color: #fff;
  background-color: var(--button-bg);
  padding: 0;
  border: 0;
  border-radius: 50%;
  width: 32px;
  height: 32px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.notification-btn {
  color: var(--main-color);
  padding: 0;
  border: 0;
  background-color: transparent;
  height: 32px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.messages-btn {
  border-radius: 4px 0 0 4px;
  position: absolute;
  right: 0;
  top: 58px;
  background-color: var(--message-btn);
  border: none;
  color: var(--main-color);
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 4px;
  display: none;
}
</style>
