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

# Server Metrics 2026-03-13 10:31:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 97080.8 (26h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386579
telemt_connections_bad_total 3192
telemt_handshake_timeouts_total 8098
telemt_upstream_connect_attempt_total 24485
telemt_upstream_connect_success_total 24373
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 24485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1765
telemt_me_reconnect_attempts_total 23031
telemt_me_reconnect_success_total 19511
telemt_me_reader_eof_total 20844
telemt_me_idle_close_by_peer_total 20843
telemt_me_route_drop_no_conn_total 120782
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333113
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1074
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 19824
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19495
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 332817
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 5893853216 (5.49 GB)
telemt_user_octets_to_client{user="hello"} 143976485640 (134.09 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 96973.6 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177147
telemt_connections_bad_total 1565
telemt_handshake_timeouts_total 1348
telemt_upstream_connect_attempt_total 47512
telemt_upstream_connect_success_total 46857
telemt_upstream_connect_fail_total 655
telemt_upstream_connect_attempts_per_request{bucket="1"} 47512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 655
telemt_me_keepalive_timeout_total 751
telemt_me_reconnect_attempts_total 85758
telemt_me_reconnect_success_total 25523
telemt_me_reader_eof_total 28156
telemt_me_idle_close_by_peer_total 28156
telemt_me_route_drop_no_conn_total 75855
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150516
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 20
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 27622
telemt_me_refill_failed_total 1879
telemt_me_writer_restored_same_endpoint_total 25507
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2099
telemt_user_connections_total{user="hello"} 166795
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 1729912220 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 56139204495 (52.28 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 96937.3 (26h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215524
telemt_connections_bad_total 2049
telemt_handshake_timeouts_total 4375
telemt_upstream_connect_attempt_total 26231
telemt_upstream_connect_success_total 26228
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 754
telemt_me_reconnect_attempts_total 22537
telemt_me_reconnect_success_total 21339
telemt_me_reader_eof_total 22874
telemt_me_idle_close_by_peer_total 22874
telemt_me_route_drop_no_conn_total 80691
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201190
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 21571
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21319
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 201112
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 9194626508 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 82490476528 (76.83 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 96913.0 (26h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304180
telemt_connections_bad_total 13675
telemt_handshake_timeouts_total 2235
telemt_upstream_connect_attempt_total 38949
telemt_upstream_connect_success_total 28921
telemt_upstream_connect_fail_total 10028
telemt_upstream_connect_attempts_per_request{bucket="1"} 38949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10028
telemt_me_keepalive_timeout_total 3436
telemt_me_reconnect_attempts_total 83140
telemt_me_reconnect_success_total 21223
telemt_me_reader_eof_total 23804
telemt_me_idle_close_by_peer_total 23797
telemt_me_route_drop_no_conn_total 109688
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261088
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 966
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23426
telemt_me_refill_failed_total 1930
telemt_me_writer_restored_same_endpoint_total 21213
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2203
telemt_user_connections_total{user="hello"} 263809
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 5669474846 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 98710954573 (91.93 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 47084.4 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64016
telemt_connections_bad_total 9420
telemt_handshake_timeouts_total 684
telemt_upstream_connect_attempt_total 16465
telemt_upstream_connect_success_total 16304
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 16465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 418
telemt_me_reconnect_attempts_total 17153
telemt_me_reconnect_success_total 13931
telemt_me_reader_eof_total 14832
telemt_me_idle_close_by_peer_total 14832
telemt_me_route_drop_no_conn_total 19947
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51989
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 14159
telemt_me_refill_failed_total 99
telemt_me_writer_restored_same_endpoint_total 13913
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 51984
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 477897892 (455.76 MB)
telemt_user_octets_to_client{user="hello"} 13850513312 (12.90 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 96869.5 (26h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533149
telemt_connections_bad_total 14509
telemt_handshake_timeouts_total 8568
telemt_upstream_connect_attempt_total 20689
telemt_upstream_connect_success_total 20582
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 20689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1584
telemt_me_reconnect_attempts_total 20375
telemt_me_reconnect_success_total 15758
telemt_me_reader_eof_total 16917
telemt_me_idle_close_by_peer_total 16914
telemt_me_route_drop_no_conn_total 272373
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 518284
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 438
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16110
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 15751
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 352
telemt_user_connections_total{user="hello"} 491365
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 9121486560 (8.50 GB)
telemt_user_octets_to_client{user="hello"} 274843593440 (255.97 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 67
```