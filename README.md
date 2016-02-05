# Xcode Snippets

Collection of a few code snippets I have in my Xcode.

# Installing The Snippets

## Manually

1. Ensure Xcode is closed.

2. Donwload archive from this site [ZIP](https://github.com/AleksandarPetrov/XcodeSnippets/archive/master.zip). Extract the archive.

  Or check out the project using: git clone https://github.com/AleksandarPetrov/XcodeSnippets.git

3. In terminal navigate to the new directory and run setup.sh

  Or from Finder copy files to this path: `~/Library/Developer/Xcode/UserData/CodeSnippets`

#Usage

To see the available code snippets, show the Utilities panel, to the right of your editor. On the bottom half the Utilities panel, there will be a horizontal divider with 4 icons. Click the { } icon to show the Code Snippets Library.

There are two ways to insert a snippet into your code:

1. You can drag and drop from the code snippets library into your editor:
![Xcode use code snippets drag and drop](http://nshipster.s3.amazonaws.com/xcode-snippet-drag-and-drop.gif)

2. Or for snippets that include a text completion shortcut, you can start typing that:
![Xcode use code snippets typing](http://nshipster.s3.amazonaws.com/xcode-snippet-text-completion-shortcut.gif)

Images source and more info about using snippets in Xcode [NSHipster](http://nshipster.com/xcode-snippets/).

#Snippets

###Objective C

Shortcut  | Autocompletion  | Comment
--- | --- | ---
loc             |     NSLocalizedString(`string`, `message`)  |
markca          |     #pragma mark - Custom Accessors         |
markd           |     #pragma mark - `name` Delegate  |
marka           |     #pragma mark - IBActions  |
marki           |     #pragma mark - `name` Implementation  |
markl           |     #pragma mark - `name` Lifecycle |
marko           |     #pragma mark - NSObject |
markn           |     #pragma mark - Observers and Notifications handlers |
marke           |     #pragma mark - `name` Private Extension |
markpr          |     #pragma mark - Private  |
markp           |     #pragma mark - Protocol conformance |
markpub         |     #pragma mark - Public |
marktds         |     #pragma mark - UITableViewDataSource  |
marktd          |     #pragma mark - UITableViewDelegate  |
marktfd         |     #pragma mark - UITextFieldDelegate  |
mark            |     #pragma mark - `name` |
logm            |     NSLog(@"%@ - %@", NSStringFromClass([self class]), NSStringFromSelector(_cmd))  |
@bool           |     @property (assign, nonatomic) BOOL `flag`;  |
@prop           |     @property (strong, nonatomic) `Type` *`property name`;  |
@view           |     @property (weak, nonatomic) UIView `property name`; |
@delegate       |     @property (weak, nonatomic) id<`Protocol`> `name`Delegate;  |
ro              |     readonly  |
rw              |     readwrite |
domq            |     dispatch_async(dispatch_get_main_queue(), ^{ `code`; });  |
dobq            |     dispatch_async(dispatch_get_global_queue(DISPATCH_QUEUE_PRIORITY_DEFAULT, 0), ^{ `code` }); |
setup           |     - (void)setup { `statements` }  |
shared          |     + (instancetype)sharedInstance { ... }  |   Full method using dispatch_once
core data stack |     - (void)initializeCoreDataStack { ... } |   Creates mom, psc and moc on the main queue

###Swift
Shortcut  | Autocompletion  | Comment
--- | --- | ---
mark    |   |     Mark snippet for Swift
dispatch_after    |   |     Snippet for execute code in the future
dispatch_once   |   |     Snippet for dispatch_once block inlined in a function


#To Do
More snippets.

Automate installation.

#Contributing

1. [Fork it](https://github.com/AleksandarPetrov/XcodeSnippets/fork)
2. Create your feature branch `git checkout -b my-new-feature`
3. Commit your changes `git commit -am 'Add some feature'`
4. Push to the branch `git push origin my-new-feature`
5. Create a new Pull Request
