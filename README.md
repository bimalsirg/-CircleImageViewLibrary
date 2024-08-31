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
	        implementation 'com.github.androidbulb:CircleImageViewLibrary:1.0'
	}

```
## Step 3:

> Efficient CircleImageView Canvas in your View.xml Example

```python
<LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:gravity="center">
        <com.androidbulb.circleimage.CircleImageView
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

This site was built using [GitHub Pages](https://pages.github.com/).



![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](![image](https://github.com/user-attachments/assets/e8ff8c85-17b5-4b0d-81c5-05abd0550102)
)


> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
Here are


> Useful information that users should know, even when skimming content.


> Helpful advice for doing things better or more easily.
> Key information users need to know to achieve their goal.
> Urgent info that needs immediate user attention to avoid problems.
> Advises about risks or negative outcomes of certain actions.

`rgb(R,G,B)` 

`rgb(9, 105, 218)`

<pre> ```python def example_function(): # Your code here print("Hello, World!") ``` </pre>

# Example Code

Here’s an example of a Python function:

```python
def example_function():
    # Your code here
    print("Hello, World!")
