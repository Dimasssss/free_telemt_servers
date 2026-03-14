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

# Server Metrics 2026-03-14 12:53:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 192030.6 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763026
telemt_connections_bad_total 36434
telemt_handshake_timeouts_total 14566
telemt_upstream_connect_attempt_total 48654
telemt_upstream_connect_success_total 48412
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 48654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6352
telemt_me_reconnect_attempts_total 44225
telemt_me_reconnect_success_total 38454
telemt_me_reader_eof_total 41115
telemt_me_idle_close_by_peer_total 41114
telemt_me_route_drop_no_conn_total 250320
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654550
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2845
telemt_desync_full_logged_total 946
telemt_desync_suppressed_total 1899
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 1070
telemt_desync_frames_bucket_total{bucket="gt_10"} 1188
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 39047
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38434
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 593
telemt_user_connections_total{user="hello"} 654455
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 18069913246 (16.83 GB)
telemt_user_octets_to_client{user="hello"} 311581330532 (290.18 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 191923.6 (53h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376864
telemt_connections_bad_total 2881
telemt_handshake_timeouts_total 3375
telemt_upstream_connect_attempt_total 158763
telemt_upstream_connect_success_total 157349
telemt_upstream_connect_fail_total 1414
telemt_upstream_connect_attempts_per_request{bucket="1"} 158763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2537
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1414
telemt_me_keepalive_timeout_total 5730
telemt_me_reconnect_attempts_total 198064
telemt_me_reconnect_success_total 42661
telemt_me_reader_eof_total 48624
telemt_me_idle_close_by_peer_total 48624
telemt_me_route_drop_no_conn_total 129979
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250130
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 47936
telemt_me_refill_failed_total 4848
telemt_me_writer_restored_same_endpoint_total 42643
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5275
telemt_user_connections_total{user="hello"} 355023
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 3604568927 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 113833099046 (106.02 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 191887.2 (53h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433319
telemt_connections_bad_total 3336
telemt_handshake_timeouts_total 36787
telemt_upstream_connect_attempt_total 51370
telemt_upstream_connect_success_total 51361
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 51370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4354
telemt_me_reconnect_attempts_total 42999
telemt_me_reconnect_success_total 41675
telemt_me_reader_eof_total 44742
telemt_me_idle_close_by_peer_total 44742
telemt_me_route_drop_no_conn_total 159198
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377602
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 42171
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41654
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 377336
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 16253254442 (15.14 GB)
telemt_user_octets_to_client{user="hello"} 167360690019 (155.87 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 191862.9 (53h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553610
telemt_connections_bad_total 16785
telemt_handshake_timeouts_total 5351
telemt_upstream_connect_attempt_total 81632
telemt_upstream_connect_success_total 70895
telemt_upstream_connect_fail_total 10737
telemt_upstream_connect_attempts_per_request{bucket="1"} 81632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10737
telemt_me_keepalive_timeout_total 5881
telemt_me_reconnect_attempts_total 160857
telemt_me_reconnect_success_total 42277
telemt_me_reader_eof_total 47315
telemt_me_idle_close_by_peer_total 47307
telemt_me_route_drop_no_conn_total 199985
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475285
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2224
telemt_desync_full_logged_total 655
telemt_desync_suppressed_total 1569
telemt_desync_frames_bucket_total{bucket="1_2"} 520
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46465
telemt_me_refill_failed_total 3697
telemt_me_writer_restored_same_endpoint_total 42267
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4188
telemt_user_connections_total{user="hello"} 494142
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 10401523767 (9.69 GB)
telemt_user_octets_to_client{user="hello"} 203864752864 (189.86 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 142034.2 (39h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242423
telemt_connections_bad_total 38856
telemt_handshake_timeouts_total 2200
telemt_upstream_connect_attempt_total 49913
telemt_upstream_connect_success_total 49406
telemt_upstream_connect_fail_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 49913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 507
telemt_me_keepalive_timeout_total 3158
telemt_me_reconnect_attempts_total 58335
telemt_me_reconnect_success_total 37453
telemt_me_reader_eof_total 40128
telemt_me_idle_close_by_peer_total 40128
telemt_me_route_drop_no_conn_total 73962
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189913
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 873
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 38454
telemt_me_refill_failed_total 648
telemt_me_writer_restored_same_endpoint_total 37435
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1001
telemt_user_connections_total{user="hello"} 194667
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 2797165681 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 89316409215 (83.18 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 191819.0 (53h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1122261
telemt_connections_bad_total 38023
telemt_handshake_timeouts_total 27446
telemt_upstream_connect_attempt_total 39912
telemt_upstream_connect_success_total 39704
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 39912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 5241
telemt_me_reconnect_attempts_total 34903
telemt_me_reconnect_success_total 30204
telemt_me_reader_eof_total 32384
telemt_me_idle_close_by_peer_total 32381
telemt_me_route_drop_no_conn_total 528452
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1040902
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 30734
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30197
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 1013523
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 21757958732 (20.26 GB)
telemt_user_octets_to_client{user="hello"} 514739568792 (479.39 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 67
```