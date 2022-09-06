<script setup></script>

<template>
  <div class="messages-section">
    <button class="messages-close">
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
        class="feather feather-x-circle"
      >
        <circle cx="12" cy="12" r="10" />
        <line x1="15" y1="9" x2="9" y2="15" />
        <line x1="9" y1="9" x2="15" y2="15" />
      </svg>
    </button>
    <div class="projects-section-header">
      <p>Client Messages</p>
    </div>
    <div class="messages">
      <div class="message-box">
        <img
          src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2550&q=80"
          alt="profile image"
        />
        <div class="message-content">
          <div class="message-header">
            <div class="name">Stephanie</div>
            <div class="star-checkbox">
              <input type="checkbox" id="star-1" />
              <label for="star-1">
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
                  class="feather feather-star"
                >
                  <polygon
                    points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"
                  />
                </svg>
              </label>
            </div>
          </div>
          <p class="message-line">
            I got your first assignment. It was quite good. 🥳 We can continue
            with the next assignment.
          </p>
          <p class="message-line time">Dec, 12</p>
        </div>
      </div>
      <div class="message-box">
        <img
          src="https://images.unsplash.com/photo-1600486913747-55e5470d6f40?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2550&q=80"
          alt="profile image"
        />
        <div class="message-content">
          <div class="message-header">
            <div class="name">Mark</div>
            <div class="star-checkbox">
              <input type="checkbox" id="star-2" />
              <label for="star-2">
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
                  class="feather feather-star"
                >
                  <polygon
                    points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"
                  />
                </svg>
              </label>
            </div>
          </div>
          <p class="message-line">
            Hey, can tell me about progress of project? I'm waiting for your
            response.
          </p>
          <p class="message-line time">Dec, 12</p>
        </div>
      </div>
      <div class="message-box">
        <img
          src="https://images.unsplash.com/photo-1543965170-4c01a586684e?ixid=MXwxMjA3fDB8MHxzZWFyY2h8NDZ8fG1hbnxlbnwwfDB8MHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=900&q=60"
          alt="profile image"
        />
        <div class="message-content">
          <div class="message-header">
            <div class="name">David</div>
            <div class="star-checkbox">
              <input type="checkbox" id="star-3" />
              <label for="star-3">
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
                  class="feather feather-star"
                >
                  <polygon
                    points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"
                  />
                </svg>
              </label>
            </div>
          </div>
          <p class="message-line">
            Awesome! 🤩 I like it. We can schedule a meeting for the next one.
          </p>
          <p class="message-line time">Dec, 12</p>
        </div>
      </div>
      <div class="message-box">
        <img
          src="https://images.unsplash.com/photo-1533993192821-2cce3a8267d1?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTl8fHdvbWFuJTIwbW9kZXJufGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=900&q=60"
          alt="profile image"
        />
        <div class="message-content">
          <div class="message-header">
            <div class="name">Jessica</div>
            <div class="star-checkbox">
              <input type="checkbox" id="star-4" />
              <label for="star-4">
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
                  class="feather feather-star"
                >
                  <polygon
                    points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"
                  />
                </svg>
              </label>
            </div>
          </div>
          <p class="message-line">
            I am really impressed! Can't wait to see the final result.
          </p>
          <p class="message-line time">Dec, 11</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.messages-section {
  flex-shrink: 0;
  padding-bottom: 32px;
  background-color: var(--projects-section);
  margin-left: 24px;
  flex: 1;
  width: 100%;
  border-radius: 30px;
  position: relative;
  overflow: auto;
  transition: all 300ms cubic-bezier(0.19, 1, 0.56, 1);

  .messages-close {
    position: absolute;
    top: 12px;
    right: 12px;
    z-index: 3;
    border: none;
    background-color: transparent;
    color: var(--main-color);
    display: none;
  }

  &.show {
    transform: translateX(0);
    opacity: 1;
    margin-left: 0;
  }

  .projects-section-header {
    position: sticky;
    top: 0;
    z-index: 1;
    padding: 5px 24px 5px 24px;
    background-color: var(--projects-section);
  }
}

.message-box {
  border-top: 1px solid var(--message-box-border);
  padding: 16px;
  display: flex;
  align-items: flex-start;
  width: 100%;

  &:hover {
    background-color: var(--message-box-hover);
    border-top-color: var(--link-color-hover);

    + .message-box {
      border-top-color: var(--link-color-hover);
    }
  }

  img {
    border-radius: 50%;
    object-fit: cover;
    width: 40px;
    height: 40px;
  }
}

.message-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;

  .name {
    font-size: 16px;
    line-height: 24px;
    font-weight: 700;
    color: var(--main-color);
    margin: 0;
  }
}

.message-content {
  padding-left: 16px;
  width: 100%;
}

.star-checkbox {
  input {
    opacity: 0;
    position: absolute;
    width: 0;
    height: 0;
  }

  label {
    width: 24px;
    height: 24px;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
  }

  .dark & {
    color: var(--secondary-color);

    input:checked + label {
      color: var(--star);
    }
  }

  input:checked + label svg {
    fill: var(--star);
    transition: 0.2s;
  }
}

.message-line {
  font-size: 14px;
  line-height: 20px;
  margin: 8px 0;
  color: var(--secondary-color);
  opacity: 0.7;

  &.time {
    text-align: right;
    margin-bottom: 0;
  }
}

.project-boxes {
  margin: 0 -8px;
  overflow-y: auto;

  &.jsGridView {
    display: flex;
    flex-wrap: wrap;

    .project-box-wrapper {
      width: 33.3%;
    }
  }

  &.jsListView {
    .project-box {
      display: flex;
      border-radius: 10px;
      position: relative;
      > * {
        margin-right: 24px;
      }
    }

    .more-wrapper {
      position: absolute;
      right: 16px;
      top: 16px;
    }

    .project-box-content-header {
      order: 1;
      max-width: 120px;
    }

    .project-box-header {
      order: 2;
    }

    .project-box-footer {
      order: 3;
      padding-top: 0;
      flex-direction: column;
      justify-content: flex-start;
    }

    .project-box-footer:after {
      display: none;
    }

    .participants {
      margin-bottom: 8px;
    }

    .project-box-content-header p {
      text-align: left;
      overflow: hidden;
      white-space: nowrap;
      text-overflow: ellipsis;
    }

    .project-box-header > span {
      position: absolute;
      bottom: 16px;
      left: 16px;
      font-size: 12px;
    }

    .box-progress-wrapper {
      order: 3;
      flex: 1;
    }
  }
}

.project-box {
  --main-color-card: #dbf6fd;
  border-radius: 30px;
  padding: 16px;
  background-color: var(--main-color-card);

  &-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 16px;
    color: var(--main-color);

    span {
      color: #4a4a4a;
      opacity: 0.7;
      font-size: 14px;
      line-height: 16px;
    }
  }

  &-content-header {
    text-align: center;
    margin-bottom: 16px;

    p {
      margin: 0;
    }
  }

  &-wrapper {
    padding: 8px;
    transition: 0.2s;
  }
}

.project-btn-more {
  padding: 0;
  height: 14px;
  width: 24px;
  height: 24px;
  position: relative;
  background-color: transparent;
  border: none;
  flex-shrink: 0;

  /*&:after, &:before {
    content: '';
    position: absolute;
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background-color: var(--main-color);
    opacity: .8;
    left: 50%;
    transform: translatex(-50%);
  }
  
  &:before { top: 0;}
  &:after { bottom: 0; }*/
}

.more-wrapper {
  position: relative;
}

.box-content-header {
  font-size: 16px;
  line-height: 24px;
  font-weight: 700;
  opacity: 0.7;
}

.box-content-subheader {
  font-size: 14px;
  line-height: 24px;
  opacity: 0.7;
}

.box-progress {
  display: block;
  height: 4px;
  border-radius: 6px;

  &-bar {
    width: 100%;
    height: 4px;
    border-radius: 6px;
    overflow: hidden;
    background-color: #fff;
    margin: 8px 0;
  }

  &-header {
    font-size: 14px;
    font-weight: 700;
    line-height: 16px;
    margin: 0;
  }

  &-wrapper {
  }

  &-percentage {
    text-align: right;
    margin: 0;
    font-size: 14px;
    font-weight: 700;
    line-height: 16px;
  }
}

.project-box-footer {
  display: flex;
  justify-content: space-between;
  padding-top: 16px;
  position: relative;

  &:after {
    content: '';
    position: absolute;
    background-color: rgba(255, 255, 255, 0.6);
    width: calc(100% + 32px);
    top: 0;
    left: -16px;
    height: 1px;
  }
}

.participants {
  display: flex;
  align-items: center;

  img {
    width: 20px;
    height: 20px;
    border-radius: 50%;
    overflow: hidden;
    object-fit: cover;

    &:not(:first-child) {
      margin-left: -8px;
    }
  }
}

.add-participant {
  width: 20px;
  height: 20px;
  border-radius: 50%;
  border: none;
  background-color: rgba(255, 255, 255, 0.6);
  margin-left: 6px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0;
}

.days-left {
  background-color: rgba(255, 255, 255, 0.6);
  font-size: 12px;
  border-radius: 20px;
  flex-shrink: 0;
  padding: 6px 16px;
  font-weight: 700;
}

.mode-switch.active .moon {
  fill: var(--main-color);
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
