1.3 Tumbler
==================

In this project, we will make a tilt switch controlled tumbler toy.

.. image:: media/1.3_header.png

Required Components
-----------------------

.. image:: media/1.3_component.png

Build the Circuit
---------------------

.. image:: media/1.3_fritzing.png


Load the Code and See What Happens
-----------------------------------------

Load the code file (``1.3_tumbler.sb3``) to Scratch 3.

The tumbler is standing when the Tilt switch is placed horizontally. If you tilt it, the tumbler will also fall. Place it horizontally again, and the tumbler will stand up again.


Tips on Sprite
----------------
Select Sprite1 and click **Costumes** in the top left corner; upload **tumbler1.png** and **tumbler2.png** from the ``home/pi/raphael-kit/scratch/picture`` path via the **Upload Costume** button; delete the default 2 costumes, and rename the sprite to **tumbler**.

.. image:: media/1.3_add_tumbler.png

Tips on Codes
--------------

.. image:: media/1.3_title2.png
  :width: 400

When the green flag is clicked, the initial state of gpio17 is set to low.

.. image:: media/1.3_title4.png
  :width: 400

When pin17 is low (the tilt switch is placed upright), we switch the tumbler sprite's costume to tumbler1 (upright state).

.. image:: media/1.3_title3.png
  :width: 400

When pin17 is high (tilt switch is tilted), switch the tumbler wizard's costume to tumbler2 (tilt state).