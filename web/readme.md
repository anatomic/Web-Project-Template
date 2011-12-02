# Web

This is where the meat of the project goes and will probably require other templates (i.e. the html email template) to be cloned into it.  If that happens, two things need to be remembered:

1.  Remove the root `.git` folder that the inner project has.  We could clone them in as submodules but we probably want to keep everything together. Saying that, if we are using a framework (like JAOSS) that uses git submodules we need to ensure that it stays linked up.
2.  If a submodule is included in a subproject we'll need to move the `.gitmodules` file from the `web` folder to the root of the project and amend the path as necessary. It's actually a lot more simple than it sounds.