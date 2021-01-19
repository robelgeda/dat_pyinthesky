##########################
Making a Pull Request (PR)
##########################

.. _dat_pyinthesky: https://github.com/spacetelescope/dat_pyinthesky

**Step 1: Open PR Tab on GitHub**

To create a pull request, navigate to the STScI `dat_pyinthesky`_ repository on GitHub and click on the
`Pull Request`:

.. image:: images/screen_shots/github_pr_tab.png
    :scale: 40%
    :align: center

**Step 2: Click New PR Button**

.. image:: images/screen_shots/github_pr_button.png
    :scale: 40%
    :align: center


**Step 3: Compare Across Forks**

.. image:: images/screen_shots/github_compare_across_forks.png
    :scale: 40%
    :align: center

**Step 4: Select Your Fork and Branch**

Use the drop down menu to select your fork and branch. If you can not find your branch, first try to refresh the page.
If you still can not find your branch, something probably went wrong in the :ref:`Git and GitHub Workflow` section.

.. image:: images/screen_shots/github_select_pr_fork_branch.png
    :scale: 50%
    :align: center

.. note::

    Make sure the `base repository` (left side) is set to the `spacetelescope/dat_pyinthesky` and `master` branch.

**Step 5: Write a Description and Create PR**

Once the PR form pops up, fill in the title with the name of your notebook or project. In the description box,
leave a description of your notebook and the data it uses.

.. tip::

    If you copy and paste the checklist in the :ref:`Check List` section, it will render as a checklist with
    radio buttons you can toggle any time.

.. image:: images/screen_shots/github_edit_pr.png
    :scale: 100%
    :align: center

.. _Updating Your PR:

**Step 6: Updating Your PR**

Once the PR is created, you can update it by pushing new changes to **your fork**. This means that you can simply follow
the steps described in the :ref:`Git and GitHub Workflow` section and GitHub will automatically update your PR to reflect the changes.

.. seealso::

    For more information on making pull request visit the
    `GitHub PR documentation <https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request>`_
