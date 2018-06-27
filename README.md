# Xcode: Swift code snippets

Some convenient code snippets I've created while desiging apps. Code snippets are a great way to become more productive with Xcode. 
If you find yourself writing the same, or similar, piece of code over and over, then it's a good candidate for a user-defined code snippet.   

### All listed snippets work with **Swift 4** 

## Snippets
```
@IBInspectable RoundButton                            Adds borderWidth, cornerRadius & borderColor
Animation_Translation_for_UIImageVIew                 FromValue & toValue with duration sample code
Animation_fromValue_toValue_with_duration             Translation with 3 values for UIImageView
AppDelegate_Firebase_Auth                             Firebase implemention
Appdelegate_programmatic_VC_Setup                     Sample code for non-Storyboard Viewcontroller implementation
Constraints_Snapkit_Typical_implementation            Typical implementation of constraints using Snapkit
Constraints_UIImage_programmatic_example              UIImage programmatic constraints example
Date_extension                                        Calculate seconds, minutes, hours, days and weeks
Delegation_implementation                             Delegation with conformity sample code
DidSet_reloadData_with_DispatchQueue                  ReloadData() w/ DispatchQueue for Array
Double_extension_Clean_percentage_value               Provides a percentage, minus .tenth place
Double_extension_round_to_fraction_digits             Extenstion for rounding to specified fraction digits
Error_enums_for_networkHelper                         Error enums for NetworkHelper 
FireBase_Auth_Service_implementation                  FireBase Auth Service implementation
Helpers_FileManager                                   FileManger implementation
Helpers_NSCacheHelper_for_UIImages                    NSCacheHelper for UIImages
Helpers_NetWorkHelper_w_data_print_out                NetWorkHelper w/ data print out to console
Helpers_NetworkHelper                                 NetworkHelper implementation for JSON Data
Helpers_UserDefaultsHelper_get_and_set                UserDefaultsHelper w/ get and set
Helpers_imageAPIClient                                ImageAPIClient singleton
Helpers_imageAPIClient_with_FileManagerHelper         ImageAPIClient with FileManagerHelper for storing Images
JSON_CodingKeys_example                               CodingKeys example. Rename incoming Data objects
JSON_mockData_example_GoT                             JSON parsing example with mockData
JSON_parsed_in_Playground                             JSON: parsed in Playground (example)
JSON_struct_codable_example                           JSON struct codable example
KeyboardHandling_Move_UIView                          Move UIView when keyBoardWillShow
Lazy_vars_UIButton_implementation                     UIButton implementation w/ target sample code
Lazy_vars_UIButton_programmatic                       UIButton programmatic implementation 
Lazy_vars_UIButton_with_states                        UIButton w/ text & states
Lazy_vars_UICollectionView_Vertical                   Programmatic implementation of a vertical collectionView
Lazy_vars_UIImage                                     Programmatic UIImage implementation
Lazy_vars_UILabel                                     Programmatic implementation of UILabel
Lazy_vars_UITableView                                 Programmatic implementation of a lazy var UITableView
Lazy_vars_UITextField                                 Programmatic implementation of a lazy var UITextfield
MARK_Section_Comment                                  Section comment for organization and separation
NavBar_configureNavBar                                BoilerPlate for configuring Navbar programmatically
Storyboard_storyboardInstance_to_ViewController       StoryboardInstance() => UIViewController
String_extension_indexOf_and_lastIndexOf              indexOf() character & lastIndexOf() in a String
String_extension_index_of_character_in_string         returns Int index of a given character in a String
TabBarController_Programmatic_NavigationVC            Programmatic TabBarController implementation
UIAlertController_actionSheet_example                 UIAlertController actionSheet example
UIAlertController_default_and_alertAction             ShowAlert with title & message. AlertAction == Ok
UIButton_custom_class_roundButton                     Implementation of a Round UIButton w/ convenience init
UIButton_state_changes_with_images                    Example of UIButton state changes with images
UICollectionView_DelegateFlowLayout_boilerPlate       CollectionView DelegateFlowLayout done programmatically
UIPickerView_programmatic_setup                       Programmatic setup of a UIPickerView
UIStackView_Pinning_extension                         Pinning extension
UITextField_extension_selective_Padding               Selective Padding Extension
UIViewController_commonInit_setupViews                CommonInit & setupViews for programmatic implementation           
UIView_Blur                                           UIView Extension for blurring & unBlurring
UIView_custom_class_GradientView                      Custom class GradientView
UIView_extension_Selectively_add_border               Add a border, color and borderwidth
UIView_extension_makeCircles_for_snapKit              UIView extension for making circles using SnapKit
UIView_extension_round_selected_corners               Selectively round Corners via UIView extension
UIView_extenstion_MakeCircles                         Extenstion for Make Corner, make circle, drawCircleInView
UIView_programmatic_implementation                    Sample code for programmatic UIView implementation
```

## How to create your own snippets

* Write your code snippet down at the code editor and select it.
* Be sure to open the code snippet library view within Xcode.
* Simply drag the selected code to the code snippet library.
* Enter a title and a short description of your snippet.
* Enter a shortcut for your snippet. You can choose any combination of letters but you should use something meaningful and you can remember easily.
* Choose a platform and the corresponding language the code snippet should be available in.
* The completion scope is also very handy to determine in which scopes (methods, class implementations, initializers, …) your code snippet should be available.
* The last step is to enter some placeholders within your code snippet. These placeholders will be shown as blue bubbles within your editor when using the code snippet and you can easily navigate to them by using your tab key. To create a placeholder just enter <#your_placeholder_name#>.

### Placeholder tokens
A placeholder makes it possible to make changes to the specific parts of the snippet at the time the snippet is added to your source code. A code snippet can have one or more placeholders, and you can tab between the placeholders as you modify the snippet in your source code.

To add a placeholder, include <#name#> in the code snippet where "name" is a string value that represents the placeholder. When the code snippet is used in your code, the placeholder will appear as a blue code bubble.

### Requirements:

* Xcode 9.0+
* Swift 3.0+

### Installation:
Code snippets are stored in your ~/Library/Developer/Xcode/UserData/CodeSnippets directory. 
Each code snippet file is a standalone plist file with a universally unique identifier (UUID), which I renamed to my liking, as the file name followed by .codesnippet as the file extension. 
This file-naming convention eliminates the chance of having conflicting file names when sharing snippets with others.

### Developer:

Clint Mejia - [clint_m@clintmejia.com](clint_m@clintmejia.com)


### License:

This project is licensed under the terms of the [MIT license](https://opensource.org/licenses/MIT).
