### Fluffy Commons ###

Various useful utilities for Android apps development.

API documentation provided as javadocs and will be generated along with jar file. See __How to build__ section.

#### Classes ####

##### Preferences & PreferencesHelper #####
Helper methods to store various values in SharedPreferences.

##### InstanceStateManager #####
Helper methods to save and restore instance state of activities and fragments.

##### ItemsAdapter & LayoutItemsAdapter #####
BaseAdapter implementations to be used with java.util.List. LayoutItemsAdapter class provides methods to populate any ViewGroup with views from adapter with optional views recycling mechanism.

##### UsefulIntents #####
Helper methods to start external apps, i.e. Email app, Calendar app and so on.

##### KeyboardHelper #####
Helper methods to show / hide keyboard and determine keyboard state.

##### ThreadSafeDateFormatter #####
Thread safe wrapper for SimpleDateFormatter.

#### How to build ####

You need [Maven](http://maven.apache.org/) to build the project. Just run `mvn clean install` from project's root, jar file and javadocs will be generated into `target` folder.

#### License ####

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.