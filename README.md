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

# Server Metrics 2026-03-12 10:09:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9386.9 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49760
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 2322
telemt_upstream_connect_attempt_total 2306
telemt_upstream_connect_success_total 2295
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 1794
telemt_me_reconnect_success_total 1781
telemt_me_reader_eof_total 1840
telemt_me_idle_close_by_peer_total 1840
telemt_me_route_drop_no_conn_total 13085
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44772
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 157
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1787
telemt_me_writer_restored_same_endpoint_total 1765
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 44746
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 676364792 (645.03 MB)
telemt_user_octets_to_client{user="hello"} 12681082516 (11.81 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9279.7 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20491
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 3371
telemt_upstream_connect_success_total 3302
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 3371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 5589
telemt_me_reconnect_success_total 2795
telemt_me_reader_eof_total 2914
telemt_me_idle_close_by_peer_total 2914
telemt_me_route_drop_no_conn_total 7477
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19535
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2884
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 2780
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 19533
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 214350844 (204.42 MB)
telemt_user_octets_to_client{user="hello"} 3959237052 (3.69 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9243.3 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28373
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 210
telemt_upstream_connect_attempt_total 2477
telemt_upstream_connect_success_total 2477
telemt_upstream_connect_attempts_per_request{bucket="1"} 2477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 1974
telemt_me_reconnect_success_total 1961
telemt_me_reader_eof_total 2031
telemt_me_idle_close_by_peer_total 2031
telemt_me_route_drop_no_conn_total 9176
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26379
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1954
telemt_me_writer_restored_same_endpoint_total 1941
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 26374
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 272061576 (259.46 MB)
telemt_user_octets_to_client{user="hello"} 25414662120 (23.67 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9218.9 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32655
telemt_connections_bad_total 1031
telemt_handshake_timeouts_total 185
telemt_upstream_connect_attempt_total 2639
telemt_upstream_connect_success_total 2572
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 2639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 2091
telemt_me_reconnect_success_total 2055
telemt_me_reader_eof_total 2138
telemt_me_idle_close_by_peer_total 2138
telemt_me_route_drop_no_conn_total 9301
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29073
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2087
telemt_me_writer_restored_same_endpoint_total 2047
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 29074
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 744778856 (710.28 MB)
telemt_user_octets_to_client{user="hello"} 11162283096 (10.40 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9188.4 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17922
telemt_connections_bad_total 1793
telemt_handshake_timeouts_total 245
telemt_upstream_connect_attempt_total 2725
telemt_upstream_connect_success_total 2618
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 2725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 8519
telemt_me_reconnect_success_total 2104
telemt_me_reader_eof_total 2292
telemt_me_idle_close_by_peer_total 2292
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 5123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15484
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 273
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2313
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2088
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 15481
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 75639996 (72.14 MB)
telemt_user_octets_to_client{user="hello"} 4072065728 (3.79 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 9175.3 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45068
telemt_connections_bad_total 539
telemt_handshake_timeouts_total 593
telemt_upstream_connect_attempt_total 1724
telemt_upstream_connect_success_total 1713
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 1219
telemt_me_reconnect_success_total 1209
telemt_me_reader_eof_total 1269
telemt_me_idle_close_by_peer_total 1269
telemt_me_route_drop_no_conn_total 19991
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42249
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 99
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1225
telemt_me_writer_restored_same_endpoint_total 1202
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 42211
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 1747400064 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 26373577552 (24.56 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 47
```