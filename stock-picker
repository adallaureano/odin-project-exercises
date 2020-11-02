def stock_selection(stocks)
    current_value = 0
    best_price = []

    stocks.each_with_index do |buy, index1|
        stocks.each_with_index do |sell, index2|
            profit = sell - buy 

            if (profit > current_value) && (sell > buy)
                current_value = profit
                best_price = [index1, index2]
            end
        end
    end
    best_price
end

p stock_selection([17,3,6,9,15,8,6,1,10])
