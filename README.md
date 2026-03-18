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

# Server Metrics 2026-03-18 15:12:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 23490.6 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 880379
telemt_connections_bad_total 67086
telemt_handshake_timeouts_total 24500
telemt_upstream_connect_attempt_total 67316
telemt_upstream_connect_success_total 66343
telemt_upstream_connect_fail_total 973
telemt_upstream_connect_attempts_per_request{bucket="1"} 67316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 973
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 520020
telemt_me_reconnect_success_total 3153
telemt_me_reader_eof_total 3491
telemt_me_idle_close_by_peer_total 3489
telemt_me_route_drop_no_conn_total 478896
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672830
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3072
telemt_desync_full_logged_total 1051
telemt_desync_suppressed_total 2021
telemt_desync_frames_bucket_total{bucket="1_2"} 860
telemt_desync_frames_bucket_total{bucket="3_10"} 1033
telemt_desync_frames_bucket_total{bucket="gt_10"} 1179
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3495
telemt_me_refill_failed_total 16834
telemt_me_writer_restored_same_endpoint_total 3047
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 730897
telemt_user_connections_current{user="hello"} 1661
telemt_user_octets_from_client{user="hello"} 10867018140 (10.12 GB)
telemt_user_octets_to_client{user="hello"} 193348914897 (180.07 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 4059.3 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484646
telemt_connections_bad_total 25356
telemt_connections_current 3821
telemt_connections_me_current 3821
telemt_handshake_timeouts_total 9479
telemt_upstream_connect_attempt_total 674
telemt_upstream_connect_success_total 670
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 426
telemt_me_reconnect_success_total 418
telemt_me_reader_eof_total 324
telemt_me_idle_close_by_peer_total 323
telemt_me_route_drop_no_conn_total 514750
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429034
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1054
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 743
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 430
telemt_desync_frames_bucket_total{bucket="gt_10"} 385
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 340
telemt_me_writer_restored_same_endpoint_total 416
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 428272
telemt_user_connections_current{user="hello"} 3821
telemt_user_octets_from_client{user="hello"} 3961651832 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 107658079868 (100.26 GB)
telemt_user_unique_ips_current{user="hello"} 1213
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 3989.1 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297587
telemt_connections_bad_total 17228
telemt_connections_current 2836
telemt_connections_me_current 2836
telemt_handshake_timeouts_total 5649
telemt_upstream_connect_attempt_total 548
telemt_upstream_connect_success_total 545
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 303
telemt_me_reconnect_success_total 300
telemt_me_reader_eof_total 300
telemt_me_idle_close_by_peer_total 300
telemt_me_route_drop_no_conn_total 187060
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260149
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 802
telemt_desync_full_logged_total 234
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 309
telemt_me_writer_restored_same_endpoint_total 283
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 260130
telemt_user_connections_current{user="hello"} 2836
telemt_user_octets_from_client{user="hello"} 4616692640 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 97013360772 (90.35 GB)
telemt_user_unique_ips_current{user="hello"} 933
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 4702.1 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500175
telemt_connections_bad_total 3857
telemt_connections_current 2725
telemt_connections_me_current 2725
telemt_handshake_timeouts_total 7271
telemt_upstream_connect_attempt_total 776
telemt_upstream_connect_success_total 771
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 479
telemt_me_reconnect_success_total 472
telemt_me_reader_eof_total 445
telemt_me_idle_close_by_peer_total 444
telemt_me_route_drop_no_conn_total 969529
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455961
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1298
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 958
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 635
telemt_desync_frames_bucket_total{bucket="gt_10"} 416
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 451
telemt_me_writer_restored_same_endpoint_total 461
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 455936
telemt_user_connections_current{user="hello"} 2725
telemt_user_octets_from_client{user="hello"} 3082135324 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 67970465232 (63.30 GB)
telemt_user_unique_ips_current{user="hello"} 850
telemt_user_unique_ips_recent_window{user="hello"} 393
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 23362.0 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1923743
telemt_connections_bad_total 169891
telemt_handshake_timeouts_total 29561
telemt_upstream_connect_attempt_total 15704
telemt_upstream_connect_success_total 15676
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2987275
telemt_me_reconnect_success_total 2830
telemt_me_reader_eof_total 2949
telemt_me_idle_close_by_peer_total 2949
telemt_me_route_drop_no_conn_total 1972686
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1586398
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4524
telemt_desync_full_logged_total 1594
telemt_desync_suppressed_total 2930
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 1759
telemt_desync_frames_bucket_total{bucket="gt_10"} 2026
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2905
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2715
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1588200
telemt_user_connections_current{user="hello"} 3172
telemt_user_octets_from_client{user="hello"} 25242937987 (23.51 GB)
telemt_user_octets_to_client{user="hello"} 529995931361 (493.60 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 1008
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 4152.5 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90754
telemt_connections_bad_total 5252
telemt_connections_current 924
telemt_connections_me_current 924
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 884
telemt_upstream_connect_attempt_total 4804
telemt_upstream_connect_success_total 4797
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 330184
telemt_me_reconnect_success_total 727
telemt_me_reader_eof_total 646
telemt_me_idle_close_by_peer_total 646
telemt_me_route_drop_no_conn_total 52291
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76786
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 168
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 647
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 716
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 80550
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 1375785833 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 14025398657 (13.06 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 3221.6 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229619
telemt_connections_bad_total 9641
telemt_connections_current 2782
telemt_connections_me_current 2782
telemt_handshake_timeouts_total 1948
telemt_upstream_connect_attempt_total 618
telemt_upstream_connect_success_total 618
telemt_upstream_connect_attempts_per_request{bucket="1"} 618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14705
telemt_me_reconnect_success_total 415
telemt_me_reader_eof_total 309
telemt_me_idle_close_by_peer_total 309
telemt_me_route_drop_no_conn_total 180235
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198044
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 484
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 324
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 354
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 198504
telemt_user_connections_current{user="hello"} 2782
telemt_user_octets_from_client{user="hello"} 2047973492 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 71404956060 (66.50 GB)
telemt_user_unique_ips_current{user="hello"} 828
telemt_user_unique_ips_recent_window{user="hello"} 371
```