# Copyright 2015 Chris Marchesi
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

source 'https://supermarket.chef.io'
extension 'halite'

cookbook 'poise', gem: 'poise'
cookbook 'ssh_keygen', gem: 'ssh_keygen'

group :test do
  cookbook 'ssh_keygen_test', path: 'test/cookbooks/ssh_keygen_test'
  cookbook 'apt'
end
