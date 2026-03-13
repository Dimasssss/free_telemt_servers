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

# Server Metrics 2026-03-13 02:05:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 66750.7 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268407
telemt_connections_bad_total 2808
telemt_handshake_timeouts_total 5635
telemt_upstream_connect_attempt_total 16915
telemt_upstream_connect_success_total 16842
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 16915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1514
telemt_me_reconnect_attempts_total 16938
telemt_me_reconnect_success_total 13459
telemt_me_reader_eof_total 14373
telemt_me_idle_close_by_peer_total 14372
telemt_me_route_drop_no_conn_total 83108
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223023
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 734
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13713
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13443
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 222790
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 3974938476 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 110476064652 (102.89 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 66643.7 (18h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124549
telemt_connections_bad_total 741
telemt_handshake_timeouts_total 981
telemt_upstream_connect_attempt_total 36906
telemt_upstream_connect_success_total 36456
telemt_upstream_connect_fail_total 450
telemt_upstream_connect_attempts_per_request{bucket="1"} 36906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 450
telemt_me_keepalive_timeout_total 474
telemt_me_reconnect_attempts_total 60839
telemt_me_reconnect_success_total 16624
telemt_me_reader_eof_total 18469
telemt_me_idle_close_by_peer_total 18469
telemt_me_route_drop_no_conn_total 44548
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101742
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 18129
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 16609
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1505
telemt_user_connections_total{user="hello"} 118242
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 1256535416 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 35524852743 (33.09 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 66607.3 (18h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150088
telemt_connections_bad_total 1732
telemt_handshake_timeouts_total 2379
telemt_upstream_connect_attempt_total 18335
telemt_upstream_connect_success_total 18333
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 369
telemt_me_reconnect_attempts_total 16127
telemt_me_reconnect_success_total 14969
telemt_me_reader_eof_total 16002
telemt_me_idle_close_by_peer_total 16002
telemt_me_route_drop_no_conn_total 57218
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140382
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15136
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14949
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 140330
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 2708512420 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 66885235372 (62.29 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 66583.0 (18h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214514
telemt_connections_bad_total 13366
telemt_handshake_timeouts_total 1428
telemt_upstream_connect_attempt_total 30702
telemt_upstream_connect_success_total 20921
telemt_upstream_connect_fail_total 9781
telemt_upstream_connect_attempts_per_request{bucket="1"} 30702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9781
telemt_me_keepalive_timeout_total 3228
telemt_me_reconnect_attempts_total 51632
telemt_me_reconnect_success_total 14732
telemt_me_reader_eof_total 16384
telemt_me_idle_close_by_peer_total 16377
telemt_me_route_drop_no_conn_total 77481
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177973
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 16092
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 14722
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1360
telemt_user_connections_total{user="hello"} 180725
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 3048463490 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 73834044845 (68.76 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16754.6 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15019
telemt_connections_bad_total 3149
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 5182
telemt_upstream_connect_success_total 5135
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 5182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 4294
telemt_me_reconnect_success_total 4279
telemt_me_reader_eof_total 4585
telemt_me_idle_close_by_peer_total 4585
telemt_me_route_drop_no_conn_total 4565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11385
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4316
telemt_me_writer_restored_same_endpoint_total 4263
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 11385
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 59364148 (56.61 MB)
telemt_user_octets_to_client{user="hello"} 5996524684 (5.58 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 66539.3 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360426
telemt_connections_bad_total 6621
telemt_handshake_timeouts_total 2791
telemt_upstream_connect_attempt_total 14121
telemt_upstream_connect_success_total 14042
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 14121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1347
telemt_me_reconnect_attempts_total 14359
telemt_me_reconnect_success_total 10738
telemt_me_reader_eof_total 11524
telemt_me_idle_close_by_peer_total 11522
telemt_me_route_drop_no_conn_total 161312
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352399
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 10984
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10731
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 340691
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 5765558868 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 193645015948 (180.35 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 29
```