# Xcode Snippets

Collection of a few code snippets I have in my Xcode.

# Installing The Snippets

## Manually

Donwload archive from this site [ZIP](https://github.com/AleksandarPetrov/XcodeSnippets/archive/master.zip).

Extract the archive.

Ensure Xcode is closed.

Add Files To The Path: `~/Library/Developer/Xcode/UserData/CodeSnippets`

Open Xcode.

#Usage

To see the available code snippets, show the Utilities panel, to the right of your editor. On the bottom half the Utilities panel, there will be a horizontal divider with 4 icons. Click the { } icon to show the Code Snippets Library.

There are two ways to insert a snippet into your code:

1. You can drag and drop from the code snippets library into your editor:
![Xcode use code snippets drag and drop](http://nshipster.s3.amazonaws.com/xcode-snippet-drag-and-drop.gif)

2. Or for snippets that include a text completion shortcut, you can start typing that:
![Xcode use code snippets typing](http://nshipster.s3.amazonaws.com/xcode-snippet-text-completion-shortcut.gif)

`Image source and more info about using snippets in Xcode [NSHipster](http://nshipster.com/xcode-snippets/)`

#Snippets

###Objective C
```
loc         Snippet for NSLocalizedString(<string>, <message>)
markca      Snippet for #pragma mark - Custom Accessors
markd       Snippet for #pragma mark - <name> Delegate
marka       Snippet for #pragma mark - IBActions
marki       Snippet for #pragma mark - <name> Implementation
markl       Snippet for #pragma mark - <name> Lifecycle
logm        Snippet for NSLog(@"%@ - %@", NSStringFromClass([self class]), NSStringFromSelector(_cmd))
marko       Snippet for #pragma mark - NSObject
markn       Snippet for #pragma mark - Observers and Notifications handlers
marke       Snippet for #pragma mark - <name> Private Extension
markpr      Snippet for #pragma mark - Private
markp       Snippet for #pragma mark - Protocol conformance
markpub     Snippet for #pragma mark - Public
marktds     Snippet for #pragma mark - UITableViewDataSource
marktd      Snippet for #pragma mark - UITableViewDelegate
marktfd     Snippet for #pragma mark - UITextFieldDelegate
mark        Snippet for #pragma mark - <name>
setup       Snippet for - (void)setup { <statements> }
```	

###Swift
```
mark      Mark snippet for Swift
```

#ToDo
More snippets.

#Contributing

1. [Fork it](https://github.com/AleksandarPetrov/XcodeSnippets/fork)
2. Create your feature branch `git checkout -b my-new-feature`
3. Commit your changes `git commit -am 'Add some feature'`
4. Push to the branch `git push origin my-new-feature`
5. Create a new Pull Request
