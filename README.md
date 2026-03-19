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

# Server Metrics 2026-03-19 04:16:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 23257.4 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319166
telemt_connections_bad_total 34399
telemt_connections_current 989
telemt_connections_me_current 989
telemt_handshake_timeouts_total 18959
telemt_upstream_connect_attempt_total 4551
telemt_upstream_connect_success_total 4481
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 4551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3341
telemt_me_reconnect_success_total 3325
telemt_me_reader_eof_total 3496
telemt_me_idle_close_by_peer_total 3496
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 80391
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231301
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1652
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 1203
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 365
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3350
telemt_me_writer_restored_same_endpoint_total 3308
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 228548
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 2558155692 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 68526177496 (63.82 GB)
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 23260.9 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573838
telemt_connections_bad_total 38886
telemt_connections_current 2295
telemt_connections_me_current 2295
telemt_handshake_timeouts_total 15904
telemt_upstream_connect_attempt_total 4362
telemt_upstream_connect_success_total 4284
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 4362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 3135
telemt_me_reconnect_success_total 3119
telemt_me_reader_eof_total 3288
telemt_me_idle_close_by_peer_total 3288
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 172246
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473155
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1810
telemt_desync_full_logged_total 616
telemt_desync_suppressed_total 1194
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 774
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3169
telemt_me_writer_restored_same_endpoint_total 3101
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 473105
telemt_user_connections_current{user="hello"} 2295
telemt_user_octets_from_client{user="hello"} 14019291748 (13.06 GB)
telemt_user_octets_to_client{user="hello"} 208753732296 (194.42 GB)
telemt_user_unique_ips_current{user="hello"} 857
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 23258.1 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476479
telemt_connections_bad_total 101082
telemt_connections_current 1907
telemt_connections_me_current 1907
telemt_handshake_timeouts_total 14007
telemt_upstream_connect_attempt_total 4300
telemt_upstream_connect_success_total 4300
telemt_upstream_connect_attempts_per_request{bucket="1"} 4300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 3150
telemt_me_reconnect_success_total 3140
telemt_me_reader_eof_total 3323
telemt_me_idle_close_by_peer_total 3323
telemt_me_route_drop_no_conn_total 142478
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345204
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1659
telemt_desync_full_logged_total 621
telemt_desync_suppressed_total 1038
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 683
telemt_desync_frames_bucket_total{bucket="gt_10"} 695
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3191
telemt_me_writer_restored_same_endpoint_total 3124
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 345202
telemt_user_connections_current{user="hello"} 1907
telemt_user_octets_from_client{user="hello"} 7470737196 (6.96 GB)
telemt_user_octets_to_client{user="hello"} 216394640304 (201.53 GB)
telemt_user_unique_ips_current{user="hello"} 707
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 23311.3 (6h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573722
telemt_connections_bad_total 69261
telemt_connections_current 1730
telemt_connections_me_current 1730
telemt_handshake_timeouts_total 11356
telemt_upstream_connect_attempt_total 4179
telemt_upstream_connect_success_total 4179
telemt_upstream_connect_attempts_per_request{bucket="1"} 4179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 3031
telemt_me_reconnect_success_total 3020
telemt_me_reader_eof_total 3182
telemt_me_idle_close_by_peer_total 3181
telemt_me_route_drop_no_conn_total 142975
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345141
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 982
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 621
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3054
telemt_me_writer_restored_same_endpoint_total 2996
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 344897
telemt_user_connections_current{user="hello"} 1730
telemt_user_octets_from_client{user="hello"} 4193281908 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 131290514672 (122.27 GB)
telemt_user_unique_ips_current{user="hello"} 656
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 23254.6 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 632329
telemt_connections_bad_total 169499
telemt_connections_current 1797
telemt_connections_me_current 1797
telemt_handshake_timeouts_total 18730
telemt_upstream_connect_attempt_total 4308
telemt_upstream_connect_success_total 4280
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3131
telemt_me_reconnect_success_total 3113
telemt_me_reader_eof_total 3287
telemt_me_idle_close_by_peer_total 3287
telemt_me_route_drop_no_conn_total 157136
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375272
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1635
telemt_desync_full_logged_total 631
telemt_desync_suppressed_total 1004
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 567
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3142
telemt_me_writer_restored_same_endpoint_total 3089
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 375188
telemt_user_connections_current{user="hello"} 1797
telemt_user_octets_from_client{user="hello"} 11216274508 (10.45 GB)
telemt_user_octets_to_client{user="hello"} 218099866012 (203.12 GB)
telemt_user_unique_ips_current{user="hello"} 738
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 23266.1 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113329
telemt_connections_bad_total 10212
telemt_connections_current 479
telemt_connections_me_current 479
telemt_handshake_timeouts_total 515
telemt_upstream_connect_attempt_total 6394
telemt_upstream_connect_success_total 6217
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 6394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 6899
telemt_me_reconnect_success_total 5060
telemt_me_reader_eof_total 5316
telemt_me_idle_close_by_peer_total 5316
telemt_me_route_drop_no_conn_total 47033
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98830
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 67
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5130
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5030
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 98820
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 1875453856 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 63484992652 (59.13 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 23257.1 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363351
telemt_connections_bad_total 38462
telemt_connections_current 1830
telemt_connections_me_current 1830
telemt_handshake_timeouts_total 18968
telemt_upstream_connect_attempt_total 4868
telemt_upstream_connect_success_total 4868
telemt_upstream_connect_attempts_per_request{bucket="1"} 4868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3719
telemt_me_reconnect_success_total 3709
telemt_me_reader_eof_total 3912
telemt_me_idle_close_by_peer_total 3912
telemt_me_route_drop_no_conn_total 103011
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294655
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1510
telemt_desync_full_logged_total 573
telemt_desync_suppressed_total 937
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 588
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3749
telemt_me_writer_restored_same_endpoint_total 3694
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 294674
telemt_user_connections_current{user="hello"} 1830
telemt_user_octets_from_client{user="hello"} 3210676608 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 165775807008 (154.39 GB)
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 201
```