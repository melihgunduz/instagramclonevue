<template>
  <div class="post">
    <!--Header-->
    <header class="header section">
      <div class="header-author">
        <Avatar :size="40" />
        <div class="header-author-info">
          <div>
            <CustomText tag="b">melih__gunduz</CustomText>
          </div>

          <div>
            <CustomText tag="b" size="xsmall">
              Bradenton Motorsports Park
            </CustomText>
          </div>
        </div>
      </div>
      <div class="header-more">
        <button type="button">
          <IconMore />
        </button>
      </div>
    </header>
    <!--Media-->

    <div class="post media">
      <img
        src="https://instagram.fadb2-1.fna.fbcdn.net/v/t51.2885-15/e35/s1080x1080/121258279_181243963620213_8026751853428538101_n.jpg?_nc_ht=instagram.fadb2-1.fna.fbcdn.net&_nc_cat=1&_nc_ohc=C4-uiWKVkuQAX-xejK8&_nc_tp=15&oh=c70ca1b4ca620d7321329c3fbb02c0a0&oe=5FAE5695"
        alt=""
      />
    </div>
    <!--Action button-->
    <div class="action-buttons section">
      <button type="button">
        <IconLike />
      </button>
      <button type="button">
        <IconComment />
      </button>
      <button type="button">
        <IconDirect />
      </button>
      <button class="action-save" type="button">
        <IconSave />
      </button>
    </div>

    <!--View count-->
    <div class="view-count section">
      <CustomText tag="b"> 8.888 Like</CustomText>
    </div>

    <!--Comment list-->

    <!--Time-->

    <!--Comment form-->
  </div>
</template>

<script>
import Avatar from '@/components/Avatar'
import CustomText from '@/components/CustomText'
import IconMore from '@/icons/more.svg'
import IconLike from '@/icons/like.svg'
import IconComment from '@/icons/comment.svg'
import IconDirect from '@/icons/direct.svg'
import IconSave from '@/icons/save.svg'
export default {
  name: 'Post',
  components: {
    Avatar,
    CustomText,
    IconMore,
    IconLike,
    IconComment,
    IconDirect,
    IconSave
  }
}
</script>

<style scoped>
.post {
  border-radius: 3px;
  border: 1px solid rgba(var(--b6a));
}
.view-count{
  background-color: red;
}
.section {
  padding-left: 16px;
  padding-right: 16px;
}
.header {
  height: 60px;
  display: flex;
  align-items: center;
  &-author {
    display: flex;
    align-items: center;

    &-info {
      margin-left: 8px;
    }
  }
  &-more {
    margin-left: auto;
  }

}

.action-buttons {
  height: 45px;
  display: flex;
  align-items: center;

  button{
    margin-right: 16px;
  }
  .action-save{
    margin-left: auto;
    margin-right: 0;
  }
}

</style>
