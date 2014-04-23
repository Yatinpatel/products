require 'test_helper'

class ProductTest < ActiveSupport::TestCase
 
    fixtures :products
 test "product is not valid without a unique title - i18n" do
 product = product.new(title: 	product(:ruby).title,
	
	description: "yyy",
	price: 1,
	image_url: "fred.gif")
assert !product.save
assert_equal "has already been taken", product.errors[:title].join('; ')
end
