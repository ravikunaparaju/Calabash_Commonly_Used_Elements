# EasyCode
Android and equivalent IOS Calabash APIs for quick reference


|Calabash Operations|        IOS              |      Android      |
|-------------------|-------------------------|-------------------|
|Touch |touch("Button id:'splash_activity_login'")|touch("Button id:'splash_activity_login_button'")
|longpress |touch_hold("UIElement")|long_press("UIElement")|
|double tap |double_tap("UIElement")|double_tap("UIElement")|
|Enter Text |enter_text("* marked:'Email address'",username)|enter_text("* id:'login_activity_credentials_username'",username)|
|Clear text from editText field|clear_text("Text_field")|perform_action("clear_text")|
|Swipe|"swipe :left", "swipe :right", "swipe :up, :offset =>{:x=> 70,:y=>560},force: :strong","swipe :down, :offset =>{:x=> 70,:y=>160},force: :strong|"perform_action("drag_coordinates",0, 1357, 0, 450, 10)","perform_action("drag_coordinates",0, 1357, 0, 450, 10)"|
|Scroll|"scroll("ScrollView",:up)","scroll("ScrollView",:down)|scroll("ScrollView",:down)"scroll("ScrollView",:up)|
|Assertions|check_element_exists("Element"), check_element_does_not_exist("Element"), check_view_with_mark_exists("some text")|check_element_exists("Element"), check_element_does_not_exist("Element"), check_view_with_mark_exists("some_text")|
|Wait|wait_for_element_exists("Element")|wait_for_element_exists("Element")|
|Map zoom in|pinch(:in)| perform_action("set_map_zoom","in")|
|Map zoom out|pinch(:out)| perform_action("set_map_zoom","out")|

**Calabash IOS core api reference**

http://www.rubydoc.info/gems/calabash-cucumber/Calabash/Cucumber/Core


**Calabash Android api reference**

http://www.rubydoc.info/gems/calabash-android/Calabash/Android/Operations



