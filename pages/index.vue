<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex>
      <v-card color="transparent" elevation="0" style="padding: 0 0 0 0; display: flex"> 
        <v-btn icon elevation="1" style="background-color: white; border: 1px solid #EBEEEF; border-radius: 6px; padding: 8px 3px 8px 6px;" max-width="32px" height="32px">
          <v-img
            alt="Logo" 
            src="/chevronLeft.svg"
            style="width: 6px; height: 10px;"
          />
        </v-btn>
        <h2 style="padding: 1px 0 18px 12px; font-size: 20px">Settings</h2>
        <v-spacer></v-spacer>
        <v-btn elevation="1" style="background-color: white; border: 1px solid #EBEEEF; border-radius: 6px; padding: 8px 16px 8px 16px " min-width="93px" height="32px">
          <v-img
            alt="Logo" 
            src="/mark.svg"
            style="width: 10px; height: 16px; margin-right: 4px"
          />
          <span style="text-transform: none; letter-spacing: 0px; font-weight: 600; font-size: 14px; color: #464748;">
            Saved
          </span>
        </v-btn>
      </v-card>

      <v-card color="white" elevation="0" width="640px" style="padding: 0 0 12px 0; border-radius: 6px; margin: 0px 0 0 0">
        <v-card-title class="title" style="padding: 16px; font-weight: 500; font-size: 18px; line-height: 100%; color: #464748;">
          Personal info
        </v-card-title>
        <v-divider style="background-color: #EBEEEF; border: 1px solid #EBEEEF;"></v-divider>
        <v-card-text style="padding: 6px 16px 0 16px">
          <v-row>
            <v-col cols="6">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/photo.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Avatar
                </span>
              </div>
              <v-card
                max-width="225px"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <div class="d-flex flex-no-wrap">
                  <div style="color: transparent; margin: 6px 0 0 -3.5px">
                    <img
                      src="/photo.png"
                      alt="avatar"
                    >
                  </div>

                  <div>
                    <v-card-title style="font-weight: 500; font-size: 10px; line-height: 100%; padding: 24px 0 8px 16px; color: #B9BEC0;">
                      JPN & PNG, 1:1, up to 2MB.
                    </v-card-title>
                    <v-btn elevation="0" style="background-color: white; border: 2px solid #EBEEEF; border-radius: 6px; padding: 8px 16px 8px 16px; margin-left: 14px" min-width="93px" height="32px">
                      <span style="text-transform: none; letter-spacing: 0px; font-weight: 600; font-size: 14px; color: #464748; margin-right: 16px">
                        New avatar
                      </span>
                    </v-btn>
                    <v-btn icon elevation="0" style="background-color: white; border: 2px solid #EBEEEF; border-radius: 6px; padding: 8px 8px 8px 8px; position: absolute; right: 0px" max-width="32px" height="32px">
                      <v-img
                        alt="Logo" 
                        src="/bin.svg"
                        style="width: 16px; height: 16px;"
                      />
                    </v-btn>
                  </div>
                </div>
              </v-card>
            </v-col>

            <v-col cols="6">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/photo.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Cover&nbsp;photo
                </span>
              </div>
              <v-card
                max-width="285px"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <div class="d-flex flex-no-wrap">
                  <div style="color: transparent; margin: 6px 0 0 -3.5px">
                    <img
                      src="/rectangle.png"
                      alt="avatar"
                    >
                  </div>

                  <div>
                    <v-card-title style="font-weight: 500; font-size: 10px; line-height: 100%; padding: 24px 0 8px 16px; color: #B9BEC0; white-space: nowrap;">
                      JPN & PNG, 4:1, up to 4MB.
                    </v-card-title>
                    <v-btn elevation="0" style="background-color: white; border: 2px solid #EBEEEF; border-radius: 6px; padding: 8px 16px 8px 16px; margin-left: 14px" min-width="93px" height="32px">
                      <span style="text-transform: none; letter-spacing: 0px; font-weight: 600; font-size: 14px; color: #464748; margin-right: 16px">
                        New cover
                      </span>
                    </v-btn>
                    <v-btn icon elevation="0" style="background-color: white; border: 2px solid #EBEEEF; border-radius: 6px; padding: 8px 8px 8px 8px; position: absolute; right: 0px" max-width="32px" height="32px">
                      <v-img
                        alt="Logo" 
                        src="/bin.svg"
                        style="width: 16px; height: 16px;"
                      />
                    </v-btn>
                  </div>
                </div>
              </v-card>
            </v-col>

            <v-col cols="6">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/text.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Your&nbsp;name&nbsp;<span style="color: red">*</span>
                </span>
              </div>
              <v-card
                max-width="100%"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <v-text-field
                  style="width: 100%; max-height: 34px; font-weight: normal; font-size: 14px; padding: 4px 0 10px 0; margin-top: 6px; border-radius: 6px; background-color: #F5F8FA;"
                  placeholder="Grigory Gulyuk"
                  rounded
                  dense
                ></v-text-field>
              </v-card>
            </v-col>

            <v-col cols="6">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/text.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Username&nbsp;<span style="color: red">*</span>
                </span>
              </div>
              <v-card
                max-width="285px"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <v-text-field
                  style="width: 100%; max-height: 34px; font-weight: normal; font-size: 14px; padding: 4px 0 10px 0; margin-top: 6px; border-radius: 6px; background-color: #F5F8FA;"
                  placeholder="@BraindeadDogge"
                  rounded
                  dense
                ></v-text-field>
              </v-card>
            </v-col>

            <v-col cols="12">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/text.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Title
                </span>
              </div>
              <v-card
                max-width="608px"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <v-text-field
                  style="width: 100%; max-height: 34px; font-weight: normal; font-size: 14px; padding: 4px 0 10px 0; margin-top: 6px; border-radius: 6px; background-color: #F5F8FA;"
                  placeholder="My cool nuxt project"
                  rounded
                  dense
                ></v-text-field>
              </v-card>
            </v-col>

            <v-col cols="12">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/link.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Personal&nbsp;website
                </span>
              </div>
              <v-card
                max-width="608px"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <v-text-field
                  style="width: 100%; max-height: 34px; font-weight: normal; font-size: 14px; padding: 4px 0 10px 0; margin-top: 6px; border-radius: 6px; background-color: #F5F8FA;"
                  placeholder="https://t.me/BraindeadDogge"
                  rounded
                  dense
                ></v-text-field>
              </v-card>
            </v-col>

            <v-col cols="12">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/text.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Bio
                </span>
              </div>
              <v-card
                max-width="608px"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <v-textarea
                  style="width: 100%; font-weight: normal; font-size: 14px; padding: 4px 0 10px 0; margin-top: 6px; border-radius: 6px; background-color: #F5F8FA;"
                  placeholder=
"Any details such as age, occupation or city.
Example: 23 y.o. designer from San Francisco."
                  rounded
                  rows="3"
                  auto-grow
                  dense
                ></v-textarea>
              </v-card>
            </v-col>

          </v-row>
        </v-card-text>
      </v-card>

      <div style="height: 20px; width: 100%"></div>

      <v-card color="white" elevation="0" width="640px" style="padding: 0 0 12px 0; border-radius: 6px; margin: 0px 0 0 0">
        <v-card-title class="title" style="padding: 16px; font-weight: 500; font-size: 18px; line-height: 100%; color: #464748;">
          Occupation
        </v-card-title>
        <v-divider style="background-color: #EBEEEF; border: 1px solid #EBEEEF;"></v-divider>
        <v-card-text style="padding: 20px 16px 0 16px">
          <span style="font-weight: normal; font-size: 14px; line-height: 17px; color: #9DA2A4;">
            We’re big on real info in Metabias,<br />
            so people know who’s who.
          </span>
          <v-row style="padding: 8px 0 0 0">
            <v-col cols="12">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/text.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Company
                </span>
              </div>
              <v-card
                max-width="608px"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <v-text-field
                  style="width: 100%; max-height: 34px; font-weight: normal; font-size: 14px; padding: 4px 0 10px 0; margin-top: 6px; border-radius: 6px; background-color: #F5F8FA;"
                  placeholder="Empty"
                  rounded
                  dense
                ></v-text-field>
              </v-card>
            </v-col>

            <v-col cols="12">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/link.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Company&nbsp;website
                </span>
              </div>
              <v-card
                max-width="608px"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <v-text-field
                  style="width: 100%; max-height: 34px; font-weight: normal; font-size: 14px; padding: 4px 0 10px 0; margin-top: 6px; border-radius: 6px; background-color: #F5F8FA;"
                  placeholder="Empty"
                  rounded
                  dense
                ></v-text-field>
              </v-card>
            </v-col>

            <v-col cols="12">
              <div style="display: flex; width: 56px; height: 12px">
                <v-img
                  alt="Logo" 
                  src="/list.svg"
                  style="max-width: 16px; max-height: 16px;"
                />
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4; padding-left: 4px">
                  Interests&nbsp;&&nbsp;skills
                </span>
              </div>
              <v-card
                max-width="608px"
                elevation="0"
                color="rgba(0,0,0,0);"
              >
                <v-text-field
                  style="width: 100%; max-height: 34px; font-weight: normal; font-size: 14px; padding: 4px 0 10px 0; margin-top: 6px; border-radius: 6px; background-color: #F5F8FA;"
                  placeholder="Empty"
                  rounded
                  dense
                ></v-text-field>
              </v-card>
            </v-col>
          </v-row>
        </v-card-text>
      </v-card>

      <div style="height: 20px; width: 100%"></div>

      <v-card color="white" elevation="0" width="640px" style="padding: 0 0 12px 0; border-radius: 6px; margin: 0px 0 0 0">
        <v-card-title class="title" style="padding: 16px; font-weight: 500; font-size: 18px; line-height: 100%; color: #464748;">
          Social networks
        </v-card-title>
        <v-divider style="background-color: #EBEEEF; border: 1px solid #EBEEEF;"></v-divider>
        <v-card-text style="padding: 20px 16px 0 16px">
          <span style="font-weight: normal; font-size: 14px; line-height: 17px; color: #9DA2A4;">
            We’re big on real info in Metabias,<br />
            so people know who’s who.
          </span>
          <v-row style="padding: 8px 0 0 0">
            <v-col cols="12">
              <div style="display: flex; width: 56px; height: 12px">
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4;">
                  Connected&nbsp;networks
                </span>
              </div>
              <div style="padding: 8px 0 0 0">
                <v-btn elevation="0" style="background-color: white; border: 1px solid #EBEEEF; border-radius: 6px; padding: 13px 13px;" height="36px">
                  <v-img
                    alt="Logo" 
                    src="/socialGoogle.svg"
                    style="width: 16px; height: 16px;"
                  />
                  <v-divider vertical style="height: 36px; margin: 0 13px; background-color: #EBEEEF; border-left: 1px solid #EBEEEF; border-right: none"/>
                  <span id="socialinput" contenteditable="true" style="height: 36px; max-width: 30ch; white-space: nowrap; overflow: hidden; text-transform: none; letter-spacing: 0px; font-weight: normal; font-size: 14px; color: #464748; align-self: center; padding-top: 10px">
                    marqtheking@gmail.com
                  </span>
                  <v-divider vertical style="height: 36px; margin: 0 13px; background-color: #EBEEEF; border-left: 1px solid #EBEEEF; border-right: none"/>
                  <v-img
                    alt="Logo" 
                    src="/cross.svg"
                    style="width: 16px; height: 16px;"
                  />
                </v-btn>
              </div>
              <div style="padding: 8px 0 0 0">
                <v-btn elevation="0" style="background-color: white; border: 1px solid #EBEEEF; border-radius: 6px; padding: 13px 13px;" height="36px">
                  <v-img
                    alt="Logo" 
                    src="/socialTwitter.svg"
                    style="width: 16px; height: 16px;"
                  />
                  <v-divider vertical style="height: 34px; margin: 0 13px; background-color: #EBEEEF; border-left: 1px solid #EBEEEF; border-right: none"/>
                  <span id="socialinput" contenteditable="true" style="height: 36px; max-width: 30ch; white-space: nowrap; overflow: hidden; text-transform: none; letter-spacing: 0px; font-weight: normal; font-size: 14px; color: #464748; align-self: center; padding-top: 10px">
                    @marques_the_king
                  </span>
                  <v-divider vertical style="height: 34px; margin: 0 13px; background-color: #EBEEEF; border-left: 1px solid #EBEEEF; border-right: none"/>
                  <v-img
                    alt="Logo" 
                    src="/cross.svg"
                    style="width: 16px; height: 16px;"
                  />
                </v-btn>
              </div>
            </v-col>

            <v-col cols="12">
              <div style="display: flex; width: 56px; height: 12px">
                <span style="text-transform: none; line-height: 100%; font-weight: 600; font-size: 12px; color: #9DA2A4;">
                  Available&nbsp;networks
                </span>
              </div>
              <div style="padding: 8px 0 0 0">
                <v-btn elevation="0" style="background-color: white; border: 1px solid #EBEEEF; border-radius: 6px; padding: 13px 13px;" height="36px">
                  <v-img
                    alt="Logo" 
                    src="/Frame.svg"
                    style="width: 16px; height: 16px;"
                  />
                  <v-divider vertical style="height: 34px; margin: 0 13px; background-color: #EBEEEF; border-left: 1px solid #EBEEEF; border-right: none"/>
                  <span style="height: 36px; text-transform: none; letter-spacing: 0px; font-weight: 600; font-size: 14px; color: #464748; padding-top: 10px">
                    Connect&nbsp;Facebook
                  </span>
                </v-btn>
              </div>
            </v-col>
          </v-row>
        </v-card-text>
      </v-card>

      <div style="height: 20px; width: 100%"></div>

      <v-card color="white" elevation="0" width="640px" style="padding: 0 0 12px 0; border-radius: 6px; margin: 0px 0 0 0">
        <v-card-title class="title" style="padding: 16px; font-weight: 500; font-size: 18px; line-height: 100%; color: #464748;">
          Account settings
        </v-card-title>
        <v-divider style="background-color: #EBEEEF; border: 1px solid #EBEEEF;"></v-divider>
        <v-card-text style="padding: 20px 16px 0 16px">
          <span style="font-weight: normal; font-size: 14px; line-height: 17px; color: #9DA2A4;">
            Be carufel. This zone is sooo danger.
          </span>
          <v-row>
            <v-col cols="12">
              <div style="padding: 8px 0 8px 0">
                <v-btn elevation="0" style="background-color: white; border: 1px solid #EBEEEF; border-radius: 6px; padding: 13px 13px;" height="36px">
                  <span style="height: 36px; text-transform: none; letter-spacing: 0px; font-weight: 500; font-size: 14px; color: #464748; padding-top: 10px">
                    Change&nbsp;password
                  </span>
                </v-btn>
              </div>
              <div style="padding: 8px 0 0 0">
                <v-btn elevation="0" style="background-color: white; border: 1px solid #FFD0D0; border-radius: 6px; padding: 13px 13px;" height="36px">
                  <span style="height: 36px; text-transform: none; letter-spacing: 0px; font-weight: 500; font-size: 14px; color: #FF5E5E; padding-top: 10px">
                    Delete&nbsp;account
                  </span>
                </v-btn>
              </div>
            </v-col>
          </v-row>
        </v-card-text>
      </v-card>

      <div style="height: 60px; width: 100%"></div>
    </v-flex>
  </v-layout>
</template>

<style lang="css">
#socialinput:focus {
  outline: none
}
</style>

<script>
export default {
  components: {}
}
</script>
