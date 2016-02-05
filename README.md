C# null guard snippets
======================

Type `ng` for:

    if (foo = null)
    	throw new ArgumentNullException(nameof(foo));


Or type `ngs` for:

    if (string.IsNullOrEmpty(foo))
    	throw new ArgumentNullException(nameof(foo));


Import them via the Code Snippet Manager *or* copy the .snippet files to

    %USER_PROFILE%\Documents\Visual Studio Version\Code Snippets\Visual C#\My Code Snippets


There's a version without the nameof() operator in the [pre-cs6 branch](tree/pre-cs6).