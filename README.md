# Explanation of Changes:
<ul>
  
  <li>Helper Methods for Calculations:</li>
        _calculate_bit_array_size and _calculate_num_hash are now @staticmethods since they don’t need class or instance attributes.
  
  <li>Batch Addition Method:</li>
        add_elements is a helper method to add multiple elements to the Bloom filter at once, improving readability in the test script.
  
  <li>Improved Comments and Naming:</li>
        Renamed filter_element to add and check_element to contains for clearer, more conventional names.

</ul>
