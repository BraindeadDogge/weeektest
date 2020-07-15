<template>
  <v-app dark>
    <v-navigation-drawer
      app
      fixed
      permanent
      style="width: 460px;"
    >
      <v-img
        alt="Logo" 
        src="/logo.svg"
        style="width: 106px; margin: 20px 30px 20px 210px"
      />
      <v-divider></v-divider>
      <v-list rounded style="margin: 20px 30px 0 210px;" class="title">
        <v-list-item-group color="rgba(0, 0, 255, 0.7)">
          <v-list-item
            to="/"
            router
            exact
          >
            <v-list-item-action>
              <v-img
                alt="Logo" 
                src="/sidebarFeed.svg"
                style="width: 24px;"
              />
            </v-list-item-action>
            <v-list-item-content>
              <v-list-item-title>Feed</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-divider style="margin-bottom: 8px"></v-divider>
          <v-list-item
            to="/popular"
            router
            exact
          >
            <v-list-item-action>
              <v-img
                alt="Logo" 
                src="/sidebarPopular.svg"
                style="width: 24px;"
              />
            </v-list-item-action>
            <v-list-item-content>
              <v-list-item-title>Popular</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item
            to="/curated"
            router
            exact
          >
            <v-list-item-action>
              <v-img
                alt="Logo" 
                src="/sidebarCurated.svg"
                style="width: 24px;"
              />
            </v-list-item-action>
            <v-list-item-content>
              <v-list-item-title>Curated</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item
            to="/opinions"
            router
            exact
          >
            <v-list-item-action>
              <v-img
                alt="Logo" 
                src="/sidebarOpinions.svg"
                style="width: 24px;"
              />
            </v-list-item-action>
            <v-list-item-content>
              <v-list-item-title>Opinions</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item
            to="/fresh"
            router
            exact
          >
            <v-list-item-action>
              <v-img
                alt="Logo" 
                src="/sidebarFresh.svg"
                style="width: 24px;"
              />
            </v-list-item-action>
            <v-list-item-content>
              <v-list-item-title>Fresh</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </v-list-item-group>
      </v-list>

      <v-card outlined style="margin: 20px 30px 0 210px" class="rounded-lg">
        <v-list style="padding: 0 0 0 0;">
          <v-list-item-group>
            <h3 style="margin: 10px 0 10px 15px;">Trends now</h3>
            <v-divider style="margin: 0 0 0 0"></v-divider>
            <v-list-item
              to="/trending/defi"
              router
              exact
            >
              <v-list-item-action>
                <v-img
                  alt="Logo" 
                  src="/tag.svg"
                  style="width: 10px;"
                />
              </v-list-item-action>
              <v-list-item-content>
                <v-list-item-title style="font-size: 16px">defi</v-list-item-title>
                <v-list-item-subtitle style="font-size: 14px">3,124 Comments</v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item
              to="/trending/cbdc"
              router
              exact
            >
              <v-list-item-action>
                <v-img
                  alt="Logo" 
                  src="/tag.svg"
                  style="width: 10px;"
                />
              </v-list-item-action>
              <v-list-item-content>
                <v-list-item-title style="font-size: 16px">cbdc</v-list-item-title>
                <v-list-item-subtitle style="font-size: 14px">2,191 Comments</v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item
              to="/trending/tokenengineer"
              router
              exact
            >
              <v-list-item-action>
                <v-img
                  alt="Logo" 
                  src="/tag.svg"
                  style="width: 10px;"
                />
              </v-list-item-action>
              <v-list-item-content>
                <v-list-item-title style="font-size: 16px">tokenengineer</v-list-item-title>
                <v-list-item-subtitle style="font-size: 14px">2,042 Comments</v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item
              to="/trending/dapps"
              router
              exact
            >
              <v-list-item-action>
                <v-img
                  alt="Logo" 
                  src="/tag.svg"
                  style="width: 10px;"
                />
              </v-list-item-action>
              <v-list-item-content>
                <v-list-item-title style="font-size: 16px">dapps</v-list-item-title>
                <v-list-item-subtitle style="font-size: 14px">1,941 Comments</v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item
              to="/trending/dapps1"
              router
              exact
            >
              <v-list-item-action>
                <v-img
                  alt="Logo" 
                  src="/tag.svg"
                  style="width: 10px;"
                />
              </v-list-item-action>
              <v-list-item-content>
                <v-list-item-title style="font-size: 16px">dapps</v-list-item-title>
                <v-list-item-subtitle style="font-size: 14px">1,336 Comments</v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item
              exact
            >
              <v-list-item-content>
                <v-list-item-subtitle style="font-size: 14px">Show more</v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
          </v-list-item-group>
        </v-list>
      </v-card>
      
      <v-card elevation="0" class="listfooter">
        <a style="font-size: 14px">Rules</a> <br />
        <a style="font-size: 14px">Privacy policy</a> <br />
        <a style="font-size: 14px">Ads and contacts</a> <br />
        <a style="font-size: 14px; color: #464748;">Get for iOS and Android</a>
      </v-card>
      <v-img
        alt="Logo" 
        src="/mobileApp.svg"
        class="listfooterlogo"
      />
    </v-navigation-drawer>
    
    <v-navigation-drawer
      fixed
      app
      right
      floating
      style="width: 470px; background-color: #F5F8FA; padding: 0 0 0 19px"
    >
      <v-card color="transparent" elevation="0" style="padding: 12.5px 0 0 0; display: flex"> 
        <v-btn icon elevation="0" style="background-color: transparent; border: none; padding: 0; margin-right: 26px" max-width="32px" height="32px">
          <message />
        </v-btn>

        <v-btn icon elevation="0" style="background-color: transparent; border: none; padding: 0; margin-right: 26px" max-width="32px" height="32px">
          <v-img
            alt="Logo" 
            src="/bell.svg"
            style="width: 32px; height: 32px;"
          />
        </v-btn>

        <v-btn icon elevation="0" style="background-color: transparent; border: none; padding: 0; margin-right: 46px" max-width="32px" height="32px">
          <v-img
            alt="Logo" 
            src="/photo.png"
            style="width: 32px; height: 32px;"
          />
        </v-btn>

        <v-btn elevation="1" style="background-color: white; border: 1px solid #EBEEEF; border-radius: 6px; padding: 13px 13px;" height="36px">
          <span style="height: 36px; text-transform: none; letter-spacing: 0px; font-weight: bold; font-size: 14px; color: #464748; padding-top: 10px">
            New&nbsp;post
          </span>
        </v-btn>
      </v-card>
    </v-navigation-drawer>
    
    <v-main style="background-color: #F5F8FA;">
      <v-container style="width: 100%; padding: 12px 0 0 0">
        <nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<style lang="css">
.listactive {
  color: black;
  background: #F5F8FA;;
}
.normaltext {
  font-weight: normal; 
  font-size: 15px !important;
}
* {
  font-family: Helvetica Neue, Arial, sans-serif;
}

.listfooter {
  position: absolute;
  bottom: 0px;
  margin: 20px 30px 12px 220px;
  padding: 0 0 0 0;
}
.listfooterlogo {
  position: absolute;
  width: 16px;
  height: 16px;
  right: 244px;
  bottom: 16px;
}
.listfooter a {
  color: #9DA2A4;
  font-weight: normal;
  font-size: 13px;
}
</style>

<script>
import message from '../components/message.vue'

export default {
  data () {
    return {}
  },
  components: {
    message
  }
}
</script>
