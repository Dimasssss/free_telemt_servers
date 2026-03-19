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

# Server Metrics 2026-03-19 03:19:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 19883.7 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247909
telemt_connections_bad_total 29192
telemt_connections_current 701
telemt_connections_me_current 701
telemt_handshake_timeouts_total 15826
telemt_upstream_connect_attempt_total 3923
telemt_upstream_connect_success_total 3863
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 3923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2862
telemt_me_reconnect_success_total 2848
telemt_me_reader_eof_total 2985
telemt_me_idle_close_by_peer_total 2985
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 66182
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190881
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1308
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 961
telemt_desync_frames_bucket_total{bucket="1_2"} 488
telemt_desync_frames_bucket_total{bucket="3_10"} 555
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2866
telemt_me_writer_restored_same_endpoint_total 2832
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 188107
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 1981133864 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 57464934528 (53.52 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 19887.8 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452797
telemt_connections_bad_total 37337
telemt_connections_current 1886
telemt_connections_me_current 1886
telemt_handshake_timeouts_total 10851
telemt_upstream_connect_attempt_total 3811
telemt_upstream_connect_success_total 3745
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 2738
telemt_me_reconnect_success_total 2726
telemt_me_reader_eof_total 2867
telemt_me_idle_close_by_peer_total 2867
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 135371
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376582
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1394
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 911
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 560
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2767
telemt_me_writer_restored_same_endpoint_total 2710
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 376553
telemt_user_connections_current{user="hello"} 1885
telemt_user_octets_from_client{user="hello"} 12356392588 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 152238139312 (141.78 GB)
telemt_user_unique_ips_current{user="hello"} 716
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 19885.1 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372646
telemt_connections_bad_total 79807
telemt_connections_current 1386
telemt_connections_me_current 1386
telemt_handshake_timeouts_total 9200
telemt_upstream_connect_attempt_total 3762
telemt_upstream_connect_success_total 3762
telemt_upstream_connect_attempts_per_request{bucket="1"} 3762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1851
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2747
telemt_me_reconnect_success_total 2737
telemt_me_reader_eof_total 2895
telemt_me_idle_close_by_peer_total 2895
telemt_me_route_drop_no_conn_total 111316
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272645
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1315
telemt_desync_full_logged_total 499
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 551
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2780
telemt_me_writer_restored_same_endpoint_total 2721
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 272637
telemt_user_connections_current{user="hello"} 1386
telemt_user_octets_from_client{user="hello"} 5898483092 (5.49 GB)
telemt_user_octets_to_client{user="hello"} 166208145428 (154.79 GB)
telemt_user_unique_ips_current{user="hello"} 571
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 19938.2 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439388
telemt_connections_bad_total 44317
telemt_connections_current 1164
telemt_connections_me_current 1164
telemt_handshake_timeouts_total 7897
telemt_upstream_connect_attempt_total 3666
telemt_upstream_connect_success_total 3666
telemt_upstream_connect_attempts_per_request{bucket="1"} 3666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2650
telemt_me_reconnect_success_total 2639
telemt_me_reader_eof_total 2776
telemt_me_idle_close_by_peer_total 2775
telemt_me_route_drop_no_conn_total 116283
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271998
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 713
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 452
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 308
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2669
telemt_me_writer_restored_same_endpoint_total 2615
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 271733
telemt_user_connections_current{user="hello"} 1164
telemt_user_octets_from_client{user="hello"} 2408180916 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 95687752380 (89.12 GB)
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 19881.6 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 397217
telemt_connections_bad_total 33968
telemt_connections_current 1385
telemt_connections_me_current 1385
telemt_handshake_timeouts_total 14202
telemt_upstream_connect_attempt_total 3805
telemt_upstream_connect_success_total 3782
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 2774
telemt_me_reconnect_success_total 2759
telemt_me_reader_eof_total 2907
telemt_me_idle_close_by_peer_total 2907
telemt_me_route_drop_no_conn_total 116537
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294587
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1323
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 819
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 528
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2781
telemt_me_writer_restored_same_endpoint_total 2735
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 294507
telemt_user_connections_current{user="hello"} 1385
telemt_user_octets_from_client{user="hello"} 10224545804 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 169064212064 (157.45 GB)
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 19893.0 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93808
telemt_connections_bad_total 9909
telemt_connections_current 342
telemt_connections_me_current 342
telemt_handshake_timeouts_total 415
telemt_upstream_connect_attempt_total 5650
telemt_upstream_connect_success_total 5491
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 5650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2874
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_reconnect_attempts_total 6308
telemt_me_reconnect_success_total 4471
telemt_me_reader_eof_total 4690
telemt_me_idle_close_by_peer_total 4690
telemt_me_route_drop_no_conn_total 38088
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80391
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4535
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4441
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 80385
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 1629941252 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 55460271632 (51.65 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 19884.0 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276790
telemt_connections_bad_total 28291
telemt_connections_current 1344
telemt_connections_me_current 1344
telemt_handshake_timeouts_total 14201
telemt_upstream_connect_attempt_total 4236
telemt_upstream_connect_success_total 4236
telemt_upstream_connect_attempts_per_request{bucket="1"} 4236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3223
telemt_me_reconnect_success_total 3214
telemt_me_reader_eof_total 3385
telemt_me_idle_close_by_peer_total 3385
telemt_me_route_drop_no_conn_total 79570
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227372
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1176
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 723
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3250
telemt_me_writer_restored_same_endpoint_total 3199
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 227393
telemt_user_connections_current{user="hello"} 1344
telemt_user_octets_from_client{user="hello"} 2423267828 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 120514720976 (112.24 GB)
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 140
```