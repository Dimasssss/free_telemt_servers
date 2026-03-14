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

# Server Metrics 2026-03-14 10:00:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 181649.1 (50h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704797
telemt_connections_bad_total 32955
telemt_handshake_timeouts_total 13705
telemt_upstream_connect_attempt_total 46118
telemt_upstream_connect_success_total 45884
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 46118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5904
telemt_me_reconnect_attempts_total 41171
telemt_me_reconnect_success_total 36469
telemt_me_reader_eof_total 38981
telemt_me_idle_close_by_peer_total 38980
telemt_me_route_drop_no_conn_total 232895
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 603346
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2388
telemt_desync_full_logged_total 798
telemt_desync_suppressed_total 1590
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 878
telemt_desync_frames_bucket_total{bucket="gt_10"} 1001
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37008
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36449
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 603224
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 17313767642 (16.12 GB)
telemt_user_octets_to_client{user="hello"} 287638061296 (267.88 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 181542.9 (50h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354056
telemt_connections_bad_total 2815
telemt_handshake_timeouts_total 3132
telemt_upstream_connect_attempt_total 153633
telemt_upstream_connect_success_total 152287
telemt_upstream_connect_fail_total 1346
telemt_upstream_connect_attempts_per_request{bucket="1"} 153633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2446
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1346
telemt_me_keepalive_timeout_total 5422
telemt_me_reconnect_attempts_total 188231
telemt_me_reconnect_success_total 39944
telemt_me_reader_eof_total 45630
telemt_me_idle_close_by_peer_total 45630
telemt_me_route_drop_no_conn_total 121276
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231030
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 44957
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 39927
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5013
telemt_user_connections_total{user="hello"} 334134
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 3433797619 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 107009240447 (99.66 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 181506.4 (50h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410698
telemt_connections_bad_total 3217
telemt_handshake_timeouts_total 35688
telemt_upstream_connect_attempt_total 48087
telemt_upstream_connect_success_total 48078
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25999
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3715
telemt_me_reconnect_attempts_total 40298
telemt_me_reconnect_success_total 38995
telemt_me_reader_eof_total 41917
telemt_me_idle_close_by_peer_total 41917
telemt_me_route_drop_no_conn_total 149147
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357302
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 39465
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38974
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 357029
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 13815480776 (12.87 GB)
telemt_user_octets_to_client{user="hello"} 157625613560 (146.80 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 181482.1 (50h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518390
telemt_connections_bad_total 16709
telemt_handshake_timeouts_total 5210
telemt_upstream_connect_attempt_total 78544
telemt_upstream_connect_success_total 67882
telemt_upstream_connect_fail_total 10662
telemt_upstream_connect_attempts_per_request{bucket="1"} 78544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10662
telemt_me_keepalive_timeout_total 5560
telemt_me_reconnect_attempts_total 152107
telemt_me_reconnect_success_total 39811
telemt_me_reader_eof_total 44597
telemt_me_idle_close_by_peer_total 44589
telemt_me_route_drop_no_conn_total 187821
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443298
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1983
telemt_desync_full_logged_total 587
telemt_desync_suppressed_total 1396
telemt_desync_frames_bucket_total{bucket="1_2"} 467
telemt_desync_frames_bucket_total{bucket="3_10"} 764
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 43771
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 39801
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3960
telemt_user_connections_total{user="hello"} 462168
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 9928160571 (9.25 GB)
telemt_user_octets_to_client{user="hello"} 191468860432 (178.32 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 131653.6 (36h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218347
telemt_connections_bad_total 33552
telemt_handshake_timeouts_total 1966
telemt_upstream_connect_attempt_total 46429
telemt_upstream_connect_success_total 45974
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 46429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_timeout_total 2690
telemt_me_reconnect_attempts_total 50395
telemt_me_reconnect_success_total 34518
telemt_me_reader_eof_total 36943
telemt_me_idle_close_by_peer_total 36943
telemt_me_route_drop_no_conn_total 65969
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172060
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 758
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 35328
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34500
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 810
telemt_user_connections_total{user="hello"} 176819
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2648488089 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 83002439907 (77.30 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 181438.4 (50h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1049520
telemt_connections_bad_total 36938
telemt_handshake_timeouts_total 26817
telemt_upstream_connect_attempt_total 37877
telemt_upstream_connect_success_total 37676
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 37877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 4850
telemt_me_reconnect_attempts_total 33390
telemt_me_reconnect_success_total 28705
telemt_me_reader_eof_total 30783
telemt_me_idle_close_by_peer_total 30780
telemt_me_route_drop_no_conn_total 491442
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 972664
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 29211
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28698
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 945281
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 17784725852 (16.56 GB)
telemt_user_octets_to_client{user="hello"} 473827176420 (441.29 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 68
```