# -CircleImageViewLibrary
Welcome to the Efficient Canvas CircleImageView Library! This library simplifies the process of adding an optimized CircleImageView to your Android apps in android studio, sketchware,sketchware pro,etc.

# Installation
## Step 1:

> Add the JitPack repository to your build file

```python
dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' } /// For Kt use this only  maven("https://jitpack.io")
		}
	}
```
## Step 2:

> Add the dependency library // Canvas UI

```python
dependencies {
	        implementation 'com.github.bimalsirg:CircleImageViewLibrary:1.0'
	}

```
## Step 3:

> Efficient CircleImageView Canvas in your View.xml Example

```python
<LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:gravity="center">
        <com.bimalsirg.circleimage.CircleImageView
            android:id="@+id/img_icon"
            android:layout_width="150dp"
            android:layout_height="150dp"
            android:src="@drawable/test" />

    </LinearLayout>
```







# A first-level heading
## A second-level heading
### A third-level heading
 
> Text that is a quote


Use `git status` to list all new or modified files that haven't yet been committed.

This site was built using [GitHub Pages](https://bimalsirg.blogspot.com/search/label/solution/).

![Example Image](example.png)
![Example Image](https://avatars.githubusercontent.com/u/176422698?v=4)
<img src="https://example.com/image.png" alt="Example Image" width="500" />
<p align="center">
  <img src="https://example.com/image.png" alt="Example Image" width="500" />
</p>

# My Project

## Example Image

Here is an example image:

![Example Image](https://example.com/image.png)

## Image with HTML

Here is the same image with HTML for more control:

<p align="center">
  <img src="https://example.com/image.png" alt="Example Image" width="500" />
</p>

