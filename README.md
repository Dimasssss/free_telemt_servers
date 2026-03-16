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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-16 22:31:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 13544.9 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83518
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 3991
telemt_upstream_connect_attempt_total 2552
telemt_upstream_connect_success_total 2533
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1849
telemt_me_reconnect_success_total 1840
telemt_me_reader_eof_total 1925
telemt_me_idle_close_by_peer_total 1925
telemt_me_route_drop_no_conn_total 27784
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74621
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1848
telemt_me_writer_restored_same_endpoint_total 1819
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 74577
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 1389748788 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 46449815384 (43.26 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 13796.4 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61351
telemt_connections_bad_total 788
telemt_handshake_timeouts_total 2733
telemt_upstream_connect_attempt_total 3085
telemt_upstream_connect_success_total 3044
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 3085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 2332
telemt_me_reconnect_success_total 2326
telemt_me_reader_eof_total 2433
telemt_me_idle_close_by_peer_total 2433
telemt_me_route_drop_no_conn_total 24235
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55423
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2353
telemt_me_writer_restored_same_endpoint_total 2310
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 55405
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 826137408 (787.87 MB)
telemt_user_octets_to_client{user="hello"} 24836809508 (23.13 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 13572.8 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32171
telemt_connections_bad_total 401
telemt_handshake_timeouts_total 244
telemt_upstream_connect_attempt_total 3409
telemt_upstream_connect_success_total 3387
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 2696
telemt_me_reconnect_success_total 2674
telemt_me_reader_eof_total 2824
telemt_me_idle_close_by_peer_total 2824
telemt_me_route_drop_no_conn_total 11134
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30724
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2701
telemt_me_writer_restored_same_endpoint_total 2663
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 30720
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 613553764 (585.13 MB)
telemt_user_octets_to_client{user="hello"} 12131088804 (11.30 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 13631.9 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61923
telemt_connections_bad_total 2984
telemt_handshake_timeouts_total 441
telemt_upstream_connect_attempt_total 2916
telemt_upstream_connect_success_total 2879
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 2170
telemt_me_reconnect_success_total 2149
telemt_me_reader_eof_total 2251
telemt_me_idle_close_by_peer_total 2251
telemt_me_route_drop_no_conn_total 19853
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56713
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2176
telemt_me_writer_restored_same_endpoint_total 2142
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 56699
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 755391684 (720.40 MB)
telemt_user_octets_to_client{user="hello"} 24653174248 (22.96 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 13603.8 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43408
telemt_connections_bad_total 12987
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 3729
telemt_upstream_connect_success_total 3667
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 3728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 4060
telemt_me_reconnect_success_total 2949
telemt_me_reader_eof_total 3057
telemt_me_idle_close_by_peer_total 3057
telemt_me_route_drop_no_conn_total 11541
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28850
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3052
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2941
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 28846
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 240213064 (229.09 MB)
telemt_user_octets_to_client{user="hello"} 9253197076 (8.62 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 13764.8 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93993
telemt_connections_bad_total 1154
telemt_handshake_timeouts_total 810
telemt_upstream_connect_attempt_total 2689
telemt_upstream_connect_success_total 2672
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 1960
telemt_me_reconnect_success_total 1957
telemt_me_reader_eof_total 2075
telemt_me_idle_close_by_peer_total 2075
telemt_me_route_drop_no_conn_total 63428
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103449
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 67
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1985
telemt_me_writer_restored_same_endpoint_total 1947
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 88841
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 1766231716 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 52774989448 (49.15 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 1771.4 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47
telemt_connections_bad_total 11
telemt_upstream_connect_attempt_total 529
telemt_upstream_connect_success_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 225
telemt_me_reconnect_attempts_total 418
telemt_me_reconnect_success_total 414
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 412
telemt_me_route_drop_no_conn_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 412
telemt_me_writer_restored_same_endpoint_total 414
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```