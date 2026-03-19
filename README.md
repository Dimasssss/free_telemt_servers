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

# Server Metrics 2026-03-19 06:13:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 30307.2 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467560
telemt_connections_bad_total 46440
telemt_connections_current 1234
telemt_connections_me_current 1234
telemt_handshake_timeouts_total 21930
telemt_upstream_connect_attempt_total 5890
telemt_upstream_connect_success_total 5786
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 5890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5415
telemt_me_reconnect_success_total 4273
telemt_me_reader_eof_total 4529
telemt_me_idle_close_by_peer_total 4528
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 124232
telemt_me_route_drop_channel_closed_total 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348879
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2216
telemt_desync_full_logged_total 637
telemt_desync_suppressed_total 1579
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 873
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4349
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4256
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 346129
telemt_user_connections_current{user="hello"} 1234
telemt_user_octets_from_client{user="hello"} 4289258600 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 118145453768 (110.03 GB)
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 30311.2 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982127
telemt_connections_bad_total 57117
telemt_connections_current 3361
telemt_connections_me_current 3361
telemt_handshake_timeouts_total 27673
telemt_upstream_connect_attempt_total 5718
telemt_upstream_connect_success_total 5611
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 5718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 5228
telemt_me_reconnect_success_total 4083
telemt_me_reader_eof_total 4331
telemt_me_idle_close_by_peer_total 4331
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 311462
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 808849
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3399
telemt_desync_full_logged_total 1161
telemt_desync_suppressed_total 2238
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 1287
telemt_desync_frames_bucket_total{bucket="gt_10"} 1488
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4193
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4063
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 808772
telemt_user_connections_current{user="hello"} 3361
telemt_user_octets_from_client{user="hello"} 18107571456 (16.86 GB)
telemt_user_octets_to_client{user="hello"} 358558668152 (333.93 GB)
telemt_user_unique_ips_current{user="hello"} 1221
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 30361.8 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 911809
telemt_connections_bad_total 87892
telemt_connections_current 2496
telemt_connections_me_current 2496
telemt_handshake_timeouts_total 22141
telemt_upstream_connect_attempt_total 5364
telemt_upstream_connect_success_total 5364
telemt_upstream_connect_attempts_per_request{bucket="1"} 5364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 4885
telemt_me_reconnect_success_total 3835
telemt_me_reader_eof_total 4073
telemt_me_idle_close_by_peer_total 4072
telemt_me_route_drop_no_conn_total 278780
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 603822
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2278
telemt_desync_full_logged_total 827
telemt_desync_suppressed_total 1451
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 915
telemt_desync_frames_bucket_total{bucket="gt_10"} 953
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3924
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 3811
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 602731
telemt_user_connections_current{user="hello"} 2496
telemt_user_octets_from_client{user="hello"} 9541930692 (8.89 GB)
telemt_user_octets_to_client{user="hello"} 231066416176 (215.20 GB)
telemt_user_unique_ips_current{user="hello"} 855
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 30304.9 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1093212
telemt_connections_bad_total 304364
telemt_connections_current 2681
telemt_connections_me_current 2681
telemt_handshake_timeouts_total 28110
telemt_upstream_connect_attempt_total 5416
telemt_upstream_connect_success_total 5382
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 3886
telemt_me_reconnect_success_total 3860
telemt_me_reader_eof_total 4081
telemt_me_idle_close_by_peer_total 4081
telemt_me_route_drop_no_conn_total 266593
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 647097
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3231
telemt_desync_full_logged_total 1068
telemt_desync_suppressed_total 2163
telemt_desync_frames_bucket_total{bucket="1_2"} 746
telemt_desync_frames_bucket_total{bucket="3_10"} 1401
telemt_desync_frames_bucket_total{bucket="gt_10"} 1084
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 3903
telemt_me_writer_restored_same_endpoint_total 3836
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 647017
telemt_user_connections_current{user="hello"} 2681
telemt_user_octets_from_client{user="hello"} 16293593588 (15.17 GB)
telemt_user_octets_to_client{user="hello"} 346537223856 (322.74 GB)
telemt_user_unique_ips_current{user="hello"} 983
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 30316.7 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185212
telemt_connections_bad_total 11939
telemt_connections_current 643
telemt_connections_me_current 643
telemt_handshake_timeouts_total 1489
telemt_upstream_connect_attempt_total 8213
telemt_upstream_connect_success_total 8002
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 8213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4095
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 10922
telemt_me_reconnect_success_total 6484
telemt_me_reader_eof_total 6862
telemt_me_idle_close_by_peer_total 6862
telemt_me_route_drop_no_conn_total 74404
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161184
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 218
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6647
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6454
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 161179
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 2648733596 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 88000427076 (81.96 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 30307.5 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670767
telemt_connections_bad_total 83356
telemt_connections_current 2757
telemt_connections_me_current 2757
telemt_handshake_timeouts_total 29114
telemt_upstream_connect_attempt_total 6105
telemt_upstream_connect_success_total 6105
telemt_upstream_connect_attempts_per_request{bucket="1"} 6105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4606
telemt_me_reconnect_success_total 4592
telemt_me_reader_eof_total 4857
telemt_me_idle_close_by_peer_total 4857
telemt_me_route_drop_no_conn_total 236389
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 535837
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3024
telemt_desync_full_logged_total 1074
telemt_desync_suppressed_total 1950
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 1159
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4645
telemt_me_writer_restored_same_endpoint_total 4577
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 535648
telemt_user_connections_current{user="hello"} 2757
telemt_user_octets_from_client{user="hello"} 7028345692 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 306778748352 (285.71 GB)
telemt_user_unique_ips_current{user="hello"} 894
telemt_user_unique_ips_recent_window{user="hello"} 360
```