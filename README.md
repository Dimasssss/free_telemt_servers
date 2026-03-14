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

# Server Metrics 2026-03-14 09:15:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 178901.3 (49h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691821
telemt_connections_bad_total 32607
telemt_handshake_timeouts_total 13477
telemt_upstream_connect_attempt_total 45366
telemt_upstream_connect_success_total 45135
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 45366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5866
telemt_me_reconnect_attempts_total 40554
telemt_me_reconnect_success_total 35854
telemt_me_reader_eof_total 38337
telemt_me_idle_close_by_peer_total 38336
telemt_me_route_drop_no_conn_total 228860
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 591421
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2337
telemt_desync_full_logged_total 779
telemt_desync_suppressed_total 1558
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 985
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 36383
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35834
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 591305
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 17144321826 (15.97 GB)
telemt_user_octets_to_client{user="hello"} 284331823840 (264.80 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 178795.1 (49h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348212
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 3037
telemt_upstream_connect_attempt_total 153002
telemt_upstream_connect_success_total 151666
telemt_upstream_connect_fail_total 1336
telemt_upstream_connect_attempts_per_request{bucket="1"} 153002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2444
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1336
telemt_me_keepalive_timeout_total 5363
telemt_me_reconnect_attempts_total 183646
telemt_me_reconnect_success_total 39457
telemt_me_reader_eof_total 45015
telemt_me_idle_close_by_peer_total 45015
telemt_me_route_drop_no_conn_total 117803
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225489
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 44
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
telemt_me_writer_removed_unexpected_total 44341
telemt_me_refill_failed_total 4499
telemt_me_writer_restored_same_endpoint_total 39440
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4884
telemt_user_connections_total{user="hello"} 328595
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 3404959743 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 105608240607 (98.36 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 178758.8 (49h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404905
telemt_connections_bad_total 3200
telemt_handshake_timeouts_total 35616
telemt_upstream_connect_attempt_total 47448
telemt_upstream_connect_success_total 47439
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3664
telemt_me_reconnect_attempts_total 39788
telemt_me_reconnect_success_total 38490
telemt_me_reader_eof_total 41368
telemt_me_idle_close_by_peer_total 41368
telemt_me_route_drop_no_conn_total 146708
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351843
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
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 38954
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38469
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 351568
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 13722511432 (12.78 GB)
telemt_user_octets_to_client{user="hello"} 153316937504 (142.79 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 178734.3 (49h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509321
telemt_connections_bad_total 16444
telemt_handshake_timeouts_total 4641
telemt_upstream_connect_attempt_total 77597
telemt_upstream_connect_success_total 66951
telemt_upstream_connect_fail_total 10646
telemt_upstream_connect_attempts_per_request{bucket="1"} 77597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10646
telemt_me_keepalive_timeout_total 5534
telemt_me_reconnect_attempts_total 150143
telemt_me_reconnect_success_total 39019
telemt_me_reader_eof_total 43741
telemt_me_idle_close_by_peer_total 43733
telemt_me_route_drop_no_conn_total 184754
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435372
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1942
telemt_desync_full_logged_total 573
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 452
telemt_desync_frames_bucket_total{bucket="3_10"} 751
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 42937
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 39009
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3918
telemt_user_connections_total{user="hello"} 454254
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 9805512411 (9.13 GB)
telemt_user_octets_to_client{user="hello"} 189948975432 (176.90 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 128905.7 (35h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212723
telemt_connections_bad_total 32893
telemt_handshake_timeouts_total 1809
telemt_upstream_connect_attempt_total 45470
telemt_upstream_connect_success_total 45026
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 45470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 2648
telemt_me_reconnect_attempts_total 48426
telemt_me_reconnect_success_total 33705
telemt_me_reader_eof_total 36048
telemt_me_idle_close_by_peer_total 36048
telemt_me_route_drop_no_conn_total 64071
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 726
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 550
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34469
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33687
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 764
telemt_user_connections_total{user="hello"} 172120
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 2519580765 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 81404051979 (75.81 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 178690.4 (49h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1030446
telemt_connections_bad_total 36404
telemt_handshake_timeouts_total 26621
telemt_upstream_connect_attempt_total 37256
telemt_upstream_connect_success_total 37057
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 37256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 4826
telemt_me_reconnect_attempts_total 32905
telemt_me_reconnect_success_total 28220
telemt_me_reader_eof_total 30265
telemt_me_idle_close_by_peer_total 30262
telemt_me_route_drop_no_conn_total 483473
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 955061
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 796
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 535
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 28720
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28213
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 927681
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 17020438112 (15.85 GB)
telemt_user_octets_to_client{user="hello"} 461509297188 (429.81 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 56
```