[
  "4.1.15",
  "4.2.6",
  "5.0.0",
].each do |rails_version|
  appraise "activesupport-#{rails_version}" do
    gem "activesupport", rails_version
    gem "activerecord", rails_version
  end
end
