class MoviesController < ApplicationController

def mycollection
  end

  def topfavt
	@list = Spotlite::Top.new.movies
  end
  def boxoffice
	@listt = Spotlite::BoxOfficeTop.new.movies
  	
  end
  def thisweek
	@list1 = Spotlite::OpeningThisWeek.new.movies
  end
	def comingsoon
	@list2 =  Spotlite::ComingSoon.new.movies
  end
  
end
