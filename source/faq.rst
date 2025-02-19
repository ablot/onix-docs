.. _faq:

FAQ
===

.. glossary::
    
    What does ONIX stand for?
        Open Neuro Interface X, the Open Ephys implementation of the `Open
        Neuro Interface specification <https://github.com/open-ephys/ONI>`__.

    How is ONI different than ONIX?
        `Open Neuro Interface <https://github.com/open-ephys/ONI>`__ is a hardware and
        API specification designed to meet the needs of experimental neuroscientists.
        ONIX hardware and `liboni <https://github.com/open-ephys/liboni>`__ are
        implementations of the ONI specification. 

    What is Open Ephys?
        Open Ephys is a company and team of neuroscientists, engineers, and
        hackers who believe that neuroscience benefits greatly from advanced,
        well-documented, open-source hardware and software.  Have a look at the
        `Open Ephys Website <https://open-ephys.org/about-us-overview>`_ for a
        comprehensive overview of our mission and projects.

    Is ONIX hardware available for purchase?
        The system is currently in a beta test phase and will be made available on
        the `Open Ephys Store <https://open-ephys.org/store>`_ following that.

    Where do I get help when using the system?
        Have a look at the :ref:`support` page.

    Can I use :ref:`headstage_64` with a silicon probe instead of tetrodes?
        Yes. Have a look at :ref:`adapters_eibs` to see if an option exists for
        your probe. If not, :ref:`get in touch <support>` because making an adapter
        is quite simple.

    Can I use my older Intan headstages with the system?
        No. ONIX headstages use serialization hardware to allow arbitrary
        mixtures of devices to exist on the headstage. This is fundamentally
        incompatible with older, SPI-based headstages. Have a look at
        :ref:`serialization` for more information on why.

    Why is there no Open Ephys GUI plugin for ONIX hardware?
        Have a look at the :ref:`open_ephys_gui` page.

    I have existing acquisition hardware. Can I can use your API and software to acquire data from it?
        Yes, please do. Our API is explicity designed to decouple hardware
        details from software. Have a look at the :ref:`drivers` page for more
        information on integrating your hardware into the ONIX software stack.
        Depending on how your device communicates with the computer it may only
        take 10's of lines of C.

    I have existing acquisition software. Can I integrate support for ONIX hardware using your API?
        Yes, please do. Have a look at the :ref:`api_ref` to get started. Also
        let us know if you want help.

..        
..
..    Where is the firmware/gateware source code located?
..        Headstage and Host gateware is available upon request. Get in touch
..        :ref:`here <support>`.
..
..        .. note:: Before you fire off that tweet, yes, we have read and understand the `reasons
..            <http://www.ladyada.net/library/openhardware/license.html>`__ why
..            this is "bad".  The problem is that, *in practice*, we have had to
..            endure the results of making our hardware so easy to distribute
..            that people with no understanding of how it operates have sold and
..            profited from it, and *left us to deal with the destruction of
..            reputation, repairs, etc* from sub-par manufacturing and quality
..            control. If you want the gateware source, please just get in touch.
