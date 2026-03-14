# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-14 11:22:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 186532.4 (51h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732658
telemt_connections_bad_total 34241
telemt_handshake_timeouts_total 14296
telemt_upstream_connect_attempt_total 47492
telemt_upstream_connect_success_total 47257
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 47492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6141
telemt_me_reconnect_attempts_total 43331
telemt_me_reconnect_success_total 37566
telemt_me_reader_eof_total 40166
telemt_me_idle_close_by_peer_total 40165
telemt_me_route_drop_no_conn_total 242185
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628267
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2586
telemt_desync_full_logged_total 861
telemt_desync_suppressed_total 1725
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 967
telemt_desync_frames_bucket_total{bucket="gt_10"} 1075
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 38148
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37546
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 628159
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 17600568326 (16.39 GB)
telemt_user_octets_to_client{user="hello"} 302283466412 (281.52 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 186425.8 (51h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364452
telemt_connections_bad_total 2836
telemt_handshake_timeouts_total 3294
telemt_upstream_connect_attempt_total 155401
telemt_upstream_connect_success_total 154024
telemt_upstream_connect_fail_total 1376
telemt_upstream_connect_attempts_per_request{bucket="1"} 155400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2471
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1376
telemt_me_keepalive_timeout_total 5535
telemt_me_reconnect_attempts_total 192108
telemt_me_reconnect_success_total 41417
telemt_me_reader_eof_total 47204
telemt_me_idle_close_by_peer_total 47204
telemt_me_route_drop_no_conn_total 126000
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240962
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 46522
telemt_me_refill_failed_total 4701
telemt_me_writer_restored_same_endpoint_total 41399
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5105
telemt_user_connections_total{user="hello"} 344062
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 3514966159 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 111163111715 (103.53 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 186389.0 (51h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420664
telemt_connections_bad_total 3283
telemt_handshake_timeouts_total 35915
telemt_upstream_connect_attempt_total 49773
telemt_upstream_connect_success_total 49764
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 49773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3957
telemt_me_reconnect_attempts_total 41725
telemt_me_reconnect_success_total 40411
telemt_me_reader_eof_total 43386
telemt_me_idle_close_by_peer_total 43386
telemt_me_route_drop_no_conn_total 153101
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366501
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 40892
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40390
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 366222
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 14913955100 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 161449692828 (150.36 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 186364.6 (51h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533147
telemt_connections_bad_total 16753
telemt_handshake_timeouts_total 5277
telemt_upstream_connect_attempt_total 80048
telemt_upstream_connect_success_total 69355
telemt_upstream_connect_fail_total 10693
telemt_upstream_connect_attempts_per_request{bucket="1"} 80048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10693
telemt_me_keepalive_timeout_total 5729
telemt_me_reconnect_attempts_total 155672
telemt_me_reconnect_success_total 41034
telemt_me_reader_eof_total 45915
telemt_me_idle_close_by_peer_total 45907
telemt_me_route_drop_no_conn_total 193555
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457078
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2038
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 45082
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41024
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4048
telemt_user_connections_total{user="hello"} 475944
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 10106906283 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 194919188424 (181.53 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 136536.1 (37h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230178
telemt_connections_bad_total 36306
telemt_handshake_timeouts_total 2137
telemt_upstream_connect_attempt_total 47902
telemt_upstream_connect_success_total 47426
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 47902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_keepalive_timeout_total 2916
telemt_me_reconnect_attempts_total 51629
telemt_me_reconnect_success_total 35744
telemt_me_reader_eof_total 38248
telemt_me_idle_close_by_peer_total 38248
telemt_me_route_drop_no_conn_total 69708
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180697
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 786
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 36574
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35726
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 830
telemt_user_connections_total{user="hello"} 185453
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 2719938417 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 85437015835 (79.57 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 186321.7 (51h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1084623
telemt_connections_bad_total 37434
telemt_handshake_timeouts_total 27077
telemt_upstream_connect_attempt_total 38898
telemt_upstream_connect_success_total 38694
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 38898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 4946
telemt_me_reconnect_attempts_total 34186
telemt_me_reconnect_success_total 29494
telemt_me_reader_eof_total 31625
telemt_me_idle_close_by_peer_total 31622
telemt_me_route_drop_no_conn_total 508485
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005789
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 30014
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29487
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 978374
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 20826757848 (19.40 GB)
telemt_user_octets_to_client{user="hello"} 490724356828 (457.02 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 80
```