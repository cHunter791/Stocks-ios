platform :ios, '12.2'

use_frameworks!

workspace 'Stocks'

#core module
def core_pods
    pod 'RxSwift'
end

target 'Core' do
    project 'Core/Core.project'
    core_pods
end


#application
def application_pods
    core_pods
end

target 'Application' do
    project 'Application/Application.project'
    application_pods
end
