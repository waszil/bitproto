.. currentmodule:: bitproto

.. _version-0.4.5:

Version 0.4.5
-------------

- Use Python IntEnum for enum generation (respecting backward compatibility)  PR#41.

.. _version-0.4.4:

Version 0.4.4
-------------

- Minor fix compiler setup.py path issue.

.. _version-0.4.2:

Version 0.4.2
-------------

- Allow using ``type`` as message field name, fixes issue #39.

.. _version-0.4.0:

Version 0.4.0
-------------

- Add support for ``message`` and ``enum`` extensiblity for protocol backward compatibility.
- Cut down the code size of generated language-specific files.
- Refactor the bitproto compiler.
- Refactor the bitproto serialization mechanism, using language-specific libraries instead of pure compiler-generated files.
