<!DOCTYPE html>
<!-- saved from url=(0084)https://www.gnu.org/software/emacs/manual/html_node/elisp/Association-List-Type.html -->
<html><!-- Created by GNU Texinfo 7.0.3, https://www.gnu.org/software/texinfo/ --><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<title>Association List Type (GNU Emacs Lisp Reference Manual)</title>

<meta name="description" content="Association List Type (GNU Emacs Lisp Reference Manual)">
<meta name="keywords" content="Association List Type (GNU Emacs Lisp Reference Manual)">
<meta name="resource-type" content="document">
<meta name="distribution" content="global">
<meta name="Generator" content="makeinfo">
<meta name="viewport" content="width=device-width,initial-scale=1">

<link rev="made" href="mailto:bug-gnu-emacs@gnu.org">
<link rel="icon" type="image/png" href="https://www.gnu.org/graphics/gnu-head-mini.png">
<meta name="ICBM" content="42.256233,-71.006581">
<meta name="DC.title" content="gnu.org">
<style type="text/css">
@import url('/software/emacs/manual.css');
</style>
</head>

<body lang="en">
<div class="subsubsection-level-extent" id="Association-List-Type">
<div class="nav-panel">
<p>
Previous: <a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Dotted-Pair-Notation.html" accesskey="p" rel="prev">Dotted Pair Notation</a>, Up: <a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Cons-Cell-Type.html" accesskey="u" rel="up">Cons Cell and List Types</a> &nbsp; [<a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/index.html#SEC_Contents" title="Table of contents" rel="contents">Contents</a>][<a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Index.html" title="Index" rel="index">Index</a>]</p>
</div>
<hr>
<h4 class="subsubsection" id="Association-List-Type-1">2.4.6.3 Association List Type</h4>

<p>An <em class="dfn">association list</em> or <em class="dfn">alist</em> is a specially-constructed
list whose elements are cons cells.  In each element, the <small class="sc">CAR</small> is
considered a <em class="dfn">key</em>, and the <small class="sc">CDR</small> is considered an
<em class="dfn">associated value</em>.  (In some cases, the associated value is stored
in the <small class="sc">CAR</small> of the <small class="sc">CDR</small>.)  Association lists are often used as
stacks, since it is easy to add or remove associations at the front of
the list.
</p>
<p>For example,
</p>
<div class="example">
<pre class="example-preformatted">(setq alist-of-colors
      '((rose . red) (lily . white) (buttercup . yellow)))
</pre></div>

<p>sets the variable <code class="code">alist-of-colors</code> to an alist of three elements.  In the
first element, <code class="code">rose</code> is the key and <code class="code">red</code> is the value.
</p>
<p>See <a class="xref" href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Association-Lists.html">Association Lists</a>, for a further explanation of alists and for
functions that work on alists.  See <a class="xref" href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Hash-Tables.html">Hash Tables</a>, for another kind of
lookup table, which is much faster for handling a large number of keys.
</p>
</div>





</body></html>