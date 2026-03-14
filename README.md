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

# Server Metrics 2026-03-14 11:27:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 186838.0 (51h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 734278
telemt_connections_bad_total 34259
telemt_handshake_timeouts_total 14325
telemt_upstream_connect_attempt_total 47560
telemt_upstream_connect_success_total 47325
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 47560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6141
telemt_me_reconnect_attempts_total 43399
telemt_me_reconnect_success_total 37634
telemt_me_reader_eof_total 40234
telemt_me_idle_close_by_peer_total 40233
telemt_me_route_drop_no_conn_total 242582
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629786
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2597
telemt_desync_full_logged_total 865
telemt_desync_suppressed_total 1732
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 974
telemt_desync_frames_bucket_total{bucket="gt_10"} 1079
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 38216
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37614
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 629684
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 17612991946 (16.40 GB)
telemt_user_octets_to_client{user="hello"} 302838029552 (282.04 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 186730.7 (51h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365151
telemt_connections_bad_total 2837
telemt_handshake_timeouts_total 3297
telemt_upstream_connect_attempt_total 155497
telemt_upstream_connect_success_total 154120
telemt_upstream_connect_fail_total 1377
telemt_upstream_connect_attempts_per_request{bucket="1"} 155497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2471
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1377
telemt_me_keepalive_timeout_total 5539
telemt_me_reconnect_attempts_total 193405
telemt_me_reconnect_success_total 41497
telemt_me_reader_eof_total 47322
telemt_me_idle_close_by_peer_total 47322
telemt_me_route_drop_no_conn_total 126186
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241629
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
telemt_me_writer_removed_unexpected_total 46640
telemt_me_refill_failed_total 4739
telemt_me_writer_restored_same_endpoint_total 41479
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5143
telemt_user_connections_total{user="hello"} 344729
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 3518288339 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 111451845083 (103.80 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 186694.4 (51h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421945
telemt_connections_bad_total 3283
telemt_handshake_timeouts_total 36152
telemt_upstream_connect_attempt_total 49907
telemt_upstream_connect_success_total 49898
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 49907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3997
telemt_me_reconnect_attempts_total 41804
telemt_me_reconnect_success_total 40485
telemt_me_reader_eof_total 43498
telemt_me_idle_close_by_peer_total 43498
telemt_me_route_drop_no_conn_total 154056
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367404
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
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 40973
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40464
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 367169
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 15112258710 (14.07 GB)
telemt_user_octets_to_client{user="hello"} 161607144411 (150.51 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 186670.1 (51h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 534249
telemt_connections_bad_total 16770
telemt_handshake_timeouts_total 5279
telemt_upstream_connect_attempt_total 80144
telemt_upstream_connect_success_total 69447
telemt_upstream_connect_fail_total 10697
telemt_upstream_connect_attempts_per_request{bucket="1"} 80144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10697
telemt_me_keepalive_timeout_total 5730
telemt_me_reconnect_attempts_total 155741
telemt_me_reconnect_success_total 41102
telemt_me_reader_eof_total 46002
telemt_me_idle_close_by_peer_total 45994
telemt_me_route_drop_no_conn_total 193930
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458128
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2039
telemt_desync_full_logged_total 609
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 779
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45151
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41092
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4049
telemt_user_connections_total{user="hello"} 476994
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 10112352571 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 195185932052 (181.78 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 136841.5 (38h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230947
telemt_connections_bad_total 36481
telemt_handshake_timeouts_total 2137
telemt_upstream_connect_attempt_total 47952
telemt_upstream_connect_success_total 47476
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 47952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_keepalive_timeout_total 2925
telemt_me_reconnect_attempts_total 51672
telemt_me_reconnect_success_total 35787
telemt_me_reader_eof_total 38292
telemt_me_idle_close_by_peer_total 38292
telemt_me_route_drop_no_conn_total 69927
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181270
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
telemt_me_writer_removed_unexpected_total 36618
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35769
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 831
telemt_user_connections_total{user="hello"} 186026
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 2722939313 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 85691740607 (79.81 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 186626.0 (51h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1086771
telemt_connections_bad_total 37434
telemt_handshake_timeouts_total 27084
telemt_upstream_connect_attempt_total 38994
telemt_upstream_connect_success_total 38790
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 38994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 4946
telemt_me_reconnect_attempts_total 34240
telemt_me_reconnect_success_total 29547
telemt_me_reader_eof_total 31684
telemt_me_idle_close_by_peer_total 31681
telemt_me_route_drop_no_conn_total 509687
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007863
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
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 30068
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29540
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 980449
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 20952673408 (19.51 GB)
telemt_user_octets_to_client{user="hello"} 491469628608 (457.72 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 73
```