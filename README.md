# 26-fall-intro
Demos and assignments for NWU DATA 1350 (Fall 26)

# Important Installation Instructions

Follow these steps to prevent issues syncing with this repository. You should only need to do this once. (If for some reason you need to delete your codespace, you will need to complete the steps again.)

1. Create a fork of the repository.
2. In your forked copy, click the green "Code" button then click "Create codespace on main".
3. In your codespace's terminal, enter the following commands one at a time:

<pre>
pip install datascience <br />
pip install otter-grader<br />
pip install --upgrade nbstripout <br />
nbstripout --install
</pre>

4. Install "auto-pull" from the Extensions tab on the left.

In the event that auto-pull does not appear to be working, try typing the following command in terminal. Make sure you commit or copy any unsaved work to be safe.

<pre>
git pull origin main --rebase
</pre>