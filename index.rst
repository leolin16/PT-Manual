.. Manual for Performance Testing documentation master file, created by
   sphinx-quickstart on Sun Dec 17 12:12:20 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Manual for Performance Testing's documentation!
==========================================================
This is Leo's speaking.

Coding ``with`` this.

* first
    * indented item
* second
* third

#. first
#. second
#. third

.. image:: /images/test1.png

.. caution::
    Coding with that. Some kids have problems with screen time
    and if you leave them unattended with a screen and they have
    access to things like YouTube or games, they may not stay focused
    on the task at hand.

Here is some code::

	def countAdjacent(p, c, r, yChange, xChange):
		global board
        adjacentCount = 0

        while True:
            c = c + xChange
            if c < 0 or c > 7:
                return adjacentCount

            r = r + yChange
            if r < 0 or r > 7:
                return adjacentCount

            if board[c][r] == p:
                adjacentCount = adjacentCount + 1
            else:
                return adjacentCount

And here is some C# code just in case  you wanted to see it:

.. code-block:: csharp

	private static string GetMessageFromException(Exception ex)
	{
		if (ex == null) return "";
		if (ex.InnerException != null)
		{
            return GetMessageFromException(ex.InnerException);
		}
		return ex.Message;
	}


.. table:: Comparison

    ================ =============== ====== ===========
    Platform         Self-Contained? Cost   Flexibility
    ================ =============== ====== ===========
    Raspberry Pi     No              $30    Limitless
    Lego Mindstorms  Yes             $350   Medium
    ================ =============== ====== ===========

.. table:: Comparison2

    +-----------------+-----------+------+-------------+
    | Platform        | Self      | Cost | Flexibility |
    |                 | Contained |      |             |
    +=================+===========+======+=============+
    | Raspberry Pi    | No        | $30  | Limitless   |
    +-----------------+-----------+------+-------------+
    | Lego Mindstorms | Yes       | $350 | Medium      |
    +-----------------+-----------+------+-------------+

.. list-table:: Comparison3
   :widths: 20 10 10 15
   :header-rows: 1

   * - Platform
     - Self-Contained?
     - Cost
     - Flexibility
   * - Raspberry Pi
     - No
     - $30
     - Limitless
   * - Lego Mindstorms
     - Yes
     - $350
     - Medium

.. csv-table:: Comparison4
   :header: Platform,Self-Contained?,Cost,Flexibility
   :widths: 15 10 30 30

    Raspberry Pi,No,$30,Limitless
    Lego Mindstorms,Yes,$350,Medium

https://www.arduino.cc/

Snap Circuits
-------------
This is `Snap Circuits <http://www.snapcircuits.net/>`_
is a

:doc:`/Options/justlogic`

:doc:`best starting point </Options/justlogic>`

see :ref:`Options section for justcode <hwcodeOptions>` .



.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Options:

   Options/justlogic
   Options/justcode

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Guidelines:

   Guidelines/content
   Guidelines/workflow

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
