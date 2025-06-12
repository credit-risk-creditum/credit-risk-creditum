Credit Risk Creditum Documentation
==================================

.. image:: https://badge.fury.io/py/credit-risk-creditum.svg
    :target: https://badge.fury.io/py/credit-risk-creditum
    :alt: PyPI version

.. image:: https://img.shields.io/badge/License-MIT-yellow.svg
    :target: https://opensource.org/licenses/MIT
    :alt: License: MIT

.. image:: https://img.shields.io/badge/python-3.7+-blue.svg
    :target: https://www.python.org/downloads/
    :alt: Python 3.7+

A comprehensive credit risk assessment system that evaluates both individual and corporate credit applications, integrating real-time economic indicators and advanced machine learning models.

.. toctree::
   :maxdepth: 2
   :caption: Getting Started:
   :hidden:

   installation
   quickstart
   examples

.. toctree::
   :maxdepth: 2
   :caption: User Guide:
   :hidden:

   usage
   economic_indicators
   risk_models
   cli

.. toctree::
   :maxdepth: 2
   :caption: API Reference:
   :hidden:

   api_reference
   modules

.. toctree::
   :maxdepth: 2
   :caption: Research:
   :hidden:

   publication
   methodology
   validation

.. toctree::
   :maxdepth: 1
   :caption: Development:
   :hidden:

   contributing
   changelog
   license

Key Features
------------

🏠 **Individual Credit Assessment**
   Comprehensive personal loan risk evaluation with detailed factor analysis

🏢 **Corporate Credit Assessment**
   Advanced business credit risk analysis with industry-specific considerations

📈 **Economic Indicators Integration**
   Real-time economic data influence on risk calculations and dynamic adjustments

🤖 **Machine Learning Models**
   Random Forest and Logistic Regression models for enhanced prediction accuracy

⚙️ **Configurable Parameters**
   Customizable risk thresholds and weights for different lending criteria

💻 **CLI Interface**
   Command-line tool for quick risk assessments and batch processing

Quick Installation
------------------

.. code-block:: bash

   pip install credit-risk-creditum

Quick Example
-------------

.. code-block:: python

   from credit_risk import CreditApplication
   
   # Initialize application processor
   app = CreditApplication()
   
   # Process individual application
   result = app.make_decision({
       'credit_score': 720,
       'monthly_income': 5000,
       'monthly_debt': 1500,
       'loan_amount': 20000
   }, 'individual')
   
   print(f"Decision: {result['decision']}")
   print(f"Risk Score: {result['risk_score']:.3f}")

Research Publication
--------------------

This project is based on peer-reviewed research. See our :doc:`publication` for detailed methodology and validation results.

**Download:** :download:`Research Paper <publication.pdf>`

Getting Help
------------

* **Documentation**: https://credit-risk-creditum.readthedocs.io/
* **Issues**: https://github.com/credit-risk-creditum/credit-risk-creditum/issues
* **Source Code**: https://github.com/credit-risk-creditum/credit-risk-creditum
* **PyPI Package**: https://pypi.org/project/credit-risk-creditum/

Indices and Tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
