class StoreController < ApplicationController
  def index
	@products = Product.order(:title)
	@i = -1
        @cart = current_cart
  end
end
