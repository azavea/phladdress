# phladdress

A high-performance address processing suite for the City of Philadelphia

## Overview

Got dirty addresses? Let phladdress solve your parsing and standardizing needs.
This is a lightweight Python module capable of standardizing street addresses,
intersections, and post office boxes.

## Example

    from phladdress.parser import Parser

    parser = Parser()
    comps = parser.parse('1234 MARKET STREET FIRST FLOOR')

    print comps['standardized_address']  # 1234 MARKET ST FL 1ST

## Installation

    pip install git+git://github.com/CityOfPhiladelphia/phladdress.git
