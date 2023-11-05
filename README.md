package com.yuanlrc.base;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.boot.web.servlet.ServletComponentScan;
import org.springframework.context.ConfigurableApplicationContext;
import org.springframework.data.jpa.repository.config.EnableJpaAuditing;

/**
 * 项目入口启动文件
 *
 */
@SpringBootApplication
@EnableJpaAuditing
@ServletComponentScan
public class App 
{
    private static ConfigurableApplicationContext run;

	public static void main( String[] args )
    {
    	 run = springapplication.run(App.class, args);
    }
}

	
	
	

	
	
