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

# Server Metrics 2026-03-19 06:54:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 32761.5 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539492
telemt_connections_bad_total 58123
telemt_connections_current 1278
telemt_connections_me_current 1278
telemt_handshake_timeouts_total 22912
telemt_upstream_connect_attempt_total 6364
telemt_upstream_connect_success_total 6250
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 6364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5749
telemt_me_reconnect_success_total 4602
telemt_me_reader_eof_total 4885
telemt_me_idle_close_by_peer_total 4884
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 146933
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402669
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2521
telemt_desync_full_logged_total 735
telemt_desync_suppressed_total 1786
telemt_desync_frames_bucket_total{bucket="1_2"} 840
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4687
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4585
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 399905
telemt_user_connections_current{user="hello"} 1278
telemt_user_octets_from_client{user="hello"} 5549361656 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 135372973000 (126.08 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 32765.2 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1166643
telemt_connections_bad_total 64761
telemt_connections_current 3869
telemt_connections_me_current 3869
telemt_handshake_timeouts_total 30058
telemt_upstream_connect_attempt_total 6132
telemt_upstream_connect_success_total 6019
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 6132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_reconnect_attempts_total 5506
telemt_me_reconnect_success_total 4357
telemt_me_reader_eof_total 4625
telemt_me_idle_close_by_peer_total 4625
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 387253
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 965362
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4251
telemt_desync_full_logged_total 1459
telemt_desync_suppressed_total 2792
telemt_desync_frames_bucket_total{bucket="1_2"} 759
telemt_desync_frames_bucket_total{bucket="3_10"} 1613
telemt_desync_frames_bucket_total{bucket="gt_10"} 1879
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4474
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4336
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 965299
telemt_user_connections_current{user="hello"} 3869
telemt_user_octets_from_client{user="hello"} 20142587200 (18.76 GB)
telemt_user_octets_to_client{user="hello"} 421143054212 (392.22 GB)
telemt_user_unique_ips_current{user="hello"} 1315
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 32764.1 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1006645
telemt_connections_bad_total 153200
telemt_connections_current 3056
telemt_connections_me_current 3056
telemt_handshake_timeouts_total 29628
telemt_upstream_connect_attempt_total 5940
telemt_upstream_connect_success_total 5940
telemt_upstream_connect_attempts_per_request{bucket="1"} 5940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4304
telemt_me_reconnect_success_total 4284
telemt_me_reader_eof_total 4538
telemt_me_idle_close_by_peer_total 4538
telemt_me_route_drop_no_conn_total 317529
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743811
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3621
telemt_desync_full_logged_total 1149
telemt_desync_suppressed_total 2472
telemt_desync_frames_bucket_total{bucket="1_2"} 686
telemt_desync_frames_bucket_total{bucket="3_10"} 1309
telemt_desync_frames_bucket_total{bucket="gt_10"} 1626
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4362
telemt_me_writer_restored_same_endpoint_total 4268
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 743480
telemt_user_connections_current{user="hello"} 3056
telemt_user_octets_from_client{user="hello"} 13589966716 (12.66 GB)
telemt_user_octets_to_client{user="hello"} 410123715984 (381.96 GB)
telemt_user_unique_ips_current{user="hello"} 1045
telemt_user_unique_ips_recent_window{user="hello"} 419
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 32815.5 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059205
telemt_connections_bad_total 88631
telemt_connections_current 2622
telemt_connections_me_current 2622
telemt_handshake_timeouts_total 26129
telemt_upstream_connect_attempt_total 5777
telemt_upstream_connect_success_total 5777
telemt_upstream_connect_attempts_per_request{bucket="1"} 5777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5165
telemt_me_reconnect_success_total 4111
telemt_me_reader_eof_total 4371
telemt_me_idle_close_by_peer_total 4370
telemt_me_route_drop_no_conn_total 362194
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 732612
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2799
telemt_desync_full_logged_total 997
telemt_desync_suppressed_total 1802
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 1108
telemt_desync_frames_bucket_total{bucket="gt_10"} 1189
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4202
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4087
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 731493
telemt_user_connections_current{user="hello"} 2622
telemt_user_octets_from_client{user="hello"} 11121753988 (10.36 GB)
telemt_user_octets_to_client{user="hello"} 271496410560 (252.85 GB)
telemt_user_unique_ips_current{user="hello"} 936
telemt_user_unique_ips_recent_window{user="hello"} 389
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 32758.8 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1304812
telemt_connections_bad_total 367225
telemt_connections_current 2883
telemt_connections_me_current 2883
telemt_handshake_timeouts_total 30511
telemt_upstream_connect_attempt_total 5799
telemt_upstream_connect_success_total 5762
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 5799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4136
telemt_me_reconnect_success_total 4107
telemt_me_reader_eof_total 4351
telemt_me_idle_close_by_peer_total 4351
telemt_me_route_drop_no_conn_total 319674
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 778684
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3889
telemt_desync_full_logged_total 1236
telemt_desync_suppressed_total 2653
telemt_desync_frames_bucket_total{bucket="1_2"} 875
telemt_desync_frames_bucket_total{bucket="3_10"} 1738
telemt_desync_frames_bucket_total{bucket="gt_10"} 1276
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4156
telemt_me_writer_restored_same_endpoint_total 4083
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 778478
telemt_user_connections_current{user="hello"} 2883
telemt_user_octets_from_client{user="hello"} 17898476284 (16.67 GB)
telemt_user_octets_to_client{user="hello"} 401013760568 (373.47 GB)
telemt_user_unique_ips_current{user="hello"} 1073
telemt_user_unique_ips_recent_window{user="hello"} 435
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 32770.8 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216687
telemt_connections_bad_total 12316
telemt_connections_current 778
telemt_connections_me_current 778
telemt_handshake_timeouts_total 1808
telemt_upstream_connect_attempt_total 8719
telemt_upstream_connect_success_total 8496
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 8719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_reconnect_attempts_total 11283
telemt_me_reconnect_success_total 6842
telemt_me_reader_eof_total 7243
telemt_me_idle_close_by_peer_total 7243
telemt_me_route_drop_no_conn_total 93073
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191100
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 300
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7018
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6812
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 191086
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 3038691316 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 100259067080 (93.37 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 32761.3 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806120
telemt_connections_bad_total 87662
telemt_connections_current 2994
telemt_connections_me_current 2994
telemt_handshake_timeouts_total 35077
telemt_upstream_connect_attempt_total 6636
telemt_upstream_connect_success_total 6636
telemt_upstream_connect_attempts_per_request{bucket="1"} 6636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 5033
telemt_me_reconnect_success_total 4986
telemt_me_reader_eof_total 5257
telemt_me_idle_close_by_peer_total 5257
telemt_me_route_drop_no_conn_total 279851
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653392
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3688
telemt_desync_full_logged_total 1297
telemt_desync_suppressed_total 2391
telemt_desync_frames_bucket_total{bucket="1_2"} 705
telemt_desync_frames_bucket_total{bucket="3_10"} 1419
telemt_desync_frames_bucket_total{bucket="gt_10"} 1564
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5040
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4971
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 653176
telemt_user_connections_current{user="hello"} 2994
telemt_user_octets_from_client{user="hello"} 9707406168 (9.04 GB)
telemt_user_octets_to_client{user="hello"} 376941044936 (351.05 GB)
telemt_user_unique_ips_current{user="hello"} 944
telemt_user_unique_ips_recent_window{user="hello"} 356
```