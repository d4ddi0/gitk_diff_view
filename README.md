# gitk_diff_view
a small repo to reproduce a bug in the diff viewer of gitk

The diff viewer interacts badly with a diff that includes

one space followed by <items> or </items>. in the diff context lines.

these lines appear red, even though tthey do not have an initial "-", as one
would expect.
