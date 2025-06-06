.. _contributing:

Contributor's Guide
===================

If you're reading this, you're probably interested in contributing to Niquests.
Thank you very much! Open source projects live-and-die based on the support
they receive from others, and the fact that you're even considering
contributing to the Niquests project is *very* generous of you.

This document lays out guidelines and advice for contributing to this project.
If you're thinking of contributing, please start by reading this document and
getting a feel for how contributing to this project works. If you have any
questions, feel free to reach out to `Ahmed Tahri`_.

.. _Ahmed Tahri: https://github.com/Ousret

The guide is split into sections based on the type of contribution you're
thinking of making, with a section that covers general guidelines for all
contributors.

Be Cordial
----------

    **Be cordial or be on your way**. *—Kenneth Reitz*

Niquests has one very important rule governing all forms of contribution,
including reporting bugs or requesting features. This golden rule is
"`be cordial or be on your way`_".

**All contributions are welcome**, as long as
everyone involved is treated with respect.

.. _be cordial or be on your way: https://kennethreitz.org/essays/2013/be_cordial_or_be_on_your_way 

.. _early-feedback:

Get Early Feedback
------------------

If you are contributing, do not feel the need to sit on your contribution until
it is perfectly polished and complete. It helps everyone involved for you to
seek feedback as early as you possibly can. Submitting an early, unfinished
version of your contribution for feedback in no way prejudices your chances of
getting that contribution accepted, and can save you from putting a lot of work
into a contribution that is not suitable for the project.

Contribution Suitability
------------------------

Our project maintainers have the last word on whether or not a contribution is
suitable for Niquests. All contributions will be considered carefully, but from
time to time, contributions will be rejected because they do not suit the
current goals or needs of the project.

If your contribution is rejected, don't despair! As long as you followed these
guidelines, you will have a much better chance of getting your next
contribution accepted.


Code Contributions
------------------

Steps for Submitting Code
~~~~~~~~~~~~~~~~~~~~~~~~~

When contributing code, you'll want to follow this checklist:

1. Fork the repository on GitHub.
2. Run the tests to confirm they all pass on your system. If they don't, you'll
   need to investigate why they fail. If you're unable to diagnose this
   yourself, raise it as a bug report by following the guidelines in this
   document: :ref:`bug-reports`.
3. Write tests that demonstrate your bug or feature. Ensure that they fail.
4. Make your change.
5. Run the entire test suite again, confirming that all tests pass *including
   the ones you just added*.
6. Send a GitHub Pull Request to the main repository's ``main`` branch.
   GitHub Pull Requests are the expected method of code collaboration on this
   project.

The following sub-sections go into more detail on some of the points above.

Code Review
~~~~~~~~~~~

Contributions will not be merged until they've been code reviewed. You should
implement any code review feedback unless you strongly object to it. In the
event that you object to the code review feedback, you should make your case
clearly and calmly. If, after doing so, the feedback is judged to still apply,
you must either apply the feedback or withdraw your contribution.

Code Style
~~~~~~~~~~

Niquests uses a collection of tools to ensure the code base has a consistent
style as it grows. We have these orchestrated using a tool called
`pre-commit`_. This can be installed locally and run over your changes prior
to opening a PR, and will also be run as part of the CI approval process
before a change is merged.

You can find the full list of formatting requirements specified in the
`.pre-commit-config.yaml`_ at the top level directory of Niquests.

.. _pre-commit: https://pre-commit.com/
.. _.pre-commit-config.yaml: https://github.com/jawah/niquests/blob/main/.pre-commit-config.yaml

New Contributors
~~~~~~~~~~~~~~~~

If you are new or relatively new to Open Source, welcome! Niquests IS a gentle introduction to the world of Open Source.
If you're concerned about how best to contribute, please consider mailing a maintainer (listed above) and
asking for help.

Please also check the :ref:`early-feedback` section.


Documentation Contributions
---------------------------

Documentation improvements are always welcome! The documentation files live in
the ``docs/`` directory of the codebase. They're written in
`reStructuredText`_, and use `Sphinx`_ to generate the full suite of
documentation.

When contributing documentation, please do your best to follow the style of the
documentation files. This means a soft-limit of 79 characters wide in your text
files and a semi-formal, yet friendly and approachable, prose style.

When presenting Python code, use single-quoted strings (``'hello'`` instead of
``"hello"``).

.. _reStructuredText: http://docutils.sourceforge.net/rst.html
.. _Sphinx: http://sphinx-doc.org/index.html


.. _bug-reports:

Bug Reports
-----------

Bug reports are hugely important! Before you raise one, though, please check
through the `GitHub issues`_, **both open and closed**, to confirm that the bug
hasn't been reported before. Duplicate bug reports are a huge drain on the time
of other contributors, and should be avoided as much as possible.

.. _GitHub issues: https://github.com/jawah/niquests/issues


Feature Requests
----------------

Niquests happily accept new feature. Forever? Hopefully!
