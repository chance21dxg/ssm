package com.chance.ssm.controllers;

import org.springframework.util.StringUtils;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class TestController {

    @GetMapping("/hello")
    public String hello(String name){
        if (StringUtils.isEmpty(name)){
            return "hello world";
        }
        return "hello " + name;
    }

}
