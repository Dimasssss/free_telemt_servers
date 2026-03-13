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

# Server Metrics 2026-03-13 23:14:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 142847.9 (39h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582799
telemt_connections_bad_total 18815
telemt_handshake_timeouts_total 12830
telemt_upstream_connect_attempt_total 36308
telemt_upstream_connect_success_total 36125
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 36308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5146
telemt_me_reconnect_attempts_total 33275
telemt_me_reconnect_success_total 28612
telemt_me_reader_eof_total 30565
telemt_me_idle_close_by_peer_total 30564
telemt_me_route_drop_no_conn_total 191925
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500511
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1619
telemt_desync_full_logged_total 550
telemt_desync_suppressed_total 1069
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 663
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 29078
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28596
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 500405
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 15315542950 (14.26 GB)
telemt_user_octets_to_client{user="hello"} 248516755488 (231.45 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 142740.9 (39h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297615
telemt_connections_bad_total 2157
telemt_handshake_timeouts_total 1921
telemt_upstream_connect_attempt_total 140494
telemt_upstream_connect_success_total 139448
telemt_upstream_connect_fail_total 1046
telemt_upstream_connect_attempts_per_request{bucket="1"} 140494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1046
telemt_me_keepalive_timeout_total 3728
telemt_me_reconnect_attempts_total 149709
telemt_me_reconnect_success_total 29009
telemt_me_reader_eof_total 33557
telemt_me_idle_close_by_peer_total 33557
telemt_me_route_drop_no_conn_total 91145
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179145
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 33052
telemt_me_refill_failed_total 3766
telemt_me_writer_restored_same_endpoint_total 28992
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4043
telemt_user_connections_total{user="hello"} 282257
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 2973226875 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 88685894919 (82.60 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 142704.5 (39h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347982
telemt_connections_bad_total 2701
telemt_handshake_timeouts_total 30458
telemt_upstream_connect_attempt_total 37932
telemt_upstream_connect_success_total 37926
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 37932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2877
telemt_me_reconnect_attempts_total 32016
telemt_me_reconnect_success_total 30766
telemt_me_reader_eof_total 33027
telemt_me_idle_close_by_peer_total 33027
telemt_me_route_drop_no_conn_total 123324
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302651
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 31117
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30746
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 351
telemt_user_connections_total{user="hello"} 302553
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 12420688544 (11.57 GB)
telemt_user_octets_to_client{user="hello"} 125919834852 (117.27 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 142680.0 (39h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450296
telemt_connections_bad_total 15326
telemt_handshake_timeouts_total 4250
telemt_upstream_connect_attempt_total 65506
telemt_upstream_connect_success_total 55115
telemt_upstream_connect_fail_total 10391
telemt_upstream_connect_attempts_per_request{bucket="1"} 65506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20682
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10391
telemt_me_keepalive_timeout_total 5018
telemt_me_reconnect_attempts_total 131438
telemt_me_reconnect_success_total 28963
telemt_me_reader_eof_total 33002
telemt_me_idle_close_by_peer_total 32995
telemt_me_route_drop_no_conn_total 157724
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380636
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1660
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1174
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 640
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 32526
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 28953
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3563
telemt_user_connections_total{user="hello"} 399478
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 9011073383 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 152295062360 (141.84 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 92851.6 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155295
telemt_connections_bad_total 23024
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 34289
telemt_upstream_connect_success_total 33968
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 34289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1326
telemt_me_reconnect_attempts_total 37827
telemt_me_reconnect_success_total 24424
telemt_me_reader_eof_total 26145
telemt_me_idle_close_by_peer_total 26145
telemt_me_route_drop_no_conn_total 47081
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121088
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 25076
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 24406
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 125957
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 1511087857 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 60083831795 (55.96 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 142636.1 (39h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 853145
telemt_connections_bad_total 27235
telemt_handshake_timeouts_total 25147
telemt_upstream_connect_attempt_total 29396
telemt_upstream_connect_success_total 29241
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 29396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 3395
telemt_me_reconnect_attempts_total 26823
telemt_me_reconnect_success_total 22163
telemt_me_reader_eof_total 23763
telemt_me_idle_close_by_peer_total 23760
telemt_me_route_drop_no_conn_total 406541
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797024
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 22600
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22156
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 769878
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 13248088164 (12.34 GB)
telemt_user_octets_to_client{user="hello"} 391276516728 (364.40 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 27
```