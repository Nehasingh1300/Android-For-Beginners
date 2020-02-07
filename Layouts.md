# Lesson 1

## View
A View is a rectangular area visible on the screen. It has a width and height, and sometimes a background color.<br>
 An ImageView displays an image such as an icon or photo. A TextView displays text. A Button is a TextView that is sensitive to touch: tap it with your finger and it will respond. And a ViewGroup is a big View—often invisible—that contains and positions the smaller Views inside of it.<br>
 
## ViewGroup
A View is a rectangular area on the screen. For example, a TextView displays text and an ImageView displays an image.<br>
A ViewGroup is a big View that can contain smaller Views inside of it. The smaller Views are called the children of the ViewGroup and might be TextViews or ImageViews. The ViewGroup is called the parent of its children. <br>

### Image View
A View is a rectangular area on the screen. One type of View is an ImageView, which displays an image such as an icon or a photograph.<br>

### Text View
A View is a rectangular area on the screen. One type of View is a TextView, which displays one or more lines of text.<br>
[Attributes](https://developer.android.com/reference/android/widget/TextView) 
android:text<br>
android:background<br>
android:layout_weight : wrap_content / dp {unit}<br>
android:layout_height : wrap_content / dp {unit}<br>

### Button
A View is a rectangular area on the screen. One type of View is a Button, which displays a piece of text. When touched, a properly configured Button tells the Android device to execute a method — a list of instructions, like a little program.<br>


# Lesson 2

## ViewGroups
A View is a rectangular area on the screen. For example, a TextView displays text and an ImageView displays an image.<br>
A ViewGroup is a big View that can contain smaller Views inside of it. The smaller Views are called the children of the ViewGroup and might be TextViews or ImageViews. The ViewGroup is called the parent of its children. <br>

## Root View
A View is a rectangular area on the screen. A big View can contain smaller Views, which in turn can contain even smaller ones. At any given moment, the biggest View of all—the one that contains all the others—is called the root View.<br>

## Parent
A View is a rectangular area on the screen. For example, a TextView displays text and an ImageView displays an image.

## Child

## Sibling

## Linear Layout
A View is a rectangular area on the screen. For example, a TextView displays text and an ImageView displays an image.<br>
A ViewGroup is a big View that can contain smaller Views inside of it. The smaller Views are called the children of the ViewGroup and might be TextViews or ImageViews. The ViewGroup is called the parent of its children.<br>
A LinearLayout is a common type of ViewGroup. It arranges its children in a vertical column.<br>
### Size
**Fixed dp**<br>
A particular value of height and width<br>
**wrap_content**<br>
Wrap the content to maximum length<br>
**match_parent**<br>
Wrap content to parents width<br>
**layout_weight**<br>
A View is a rectangular area on the screen. A LinearLayout is a big view that can contain smaller Views, called its children. A horizontal LinearLayout arranges its children in a row, and a vertical LinearLayout arranges them in a column.<br>
Each child in a horizontal LinearLayout can request a certain minimal amount of width for itself. If the layout is wide enough, it will have width left over after satisfying these requests.<br>
The leftover width is then parcelled out among the children that claim shares of it. The number of shares claimed by each child is called the layout weight of that child.<br>


## Relative Layout
A View is a rectangular area on the screen. For example, a TextView displays text and an ImageView displays an image.<br>
A ViewGroup is a big View that can contain smaller Views inside of it. The smaller Views are called the children of the ViewGroup and might be TextViews or ImageViews. The ViewGroup is called the parent of its children.<br>
A RelativeLayout is a common type of ViewGroup that lets us position its children relative to its own edges. For example, the three children in the illustration are placed in the corners of a RelativeLayout. A RelativeLayout also lets us arrange its children relative to each other: one child can be placed to the right of another, and can even overlap.<br>
```
   android:id="@+id/name"               // Setting Id
   android:layout_below="@id/name"
   android:layout_alignParentLeft="true"
   android:layout_toLeftOf="@+id/times"
   android:layout_alignParentRight="true"
```

