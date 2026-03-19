# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 19:49:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 9100.9 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274801
telemt_connections_bad_total 12437
telemt_connections_current 1184
telemt_connections_me_current 1184
telemt_handshake_timeouts_total 2759
telemt_upstream_connect_attempt_total 1392
telemt_upstream_connect_success_total 1377
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 879
telemt_me_reconnect_success_total 872
telemt_me_reader_eof_total 906
telemt_me_idle_close_by_peer_total 906
telemt_me_route_drop_no_conn_total 82039
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215262
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1078
telemt_desync_full_logged_total 353
telemt_desync_suppressed_total 725
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 894
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 215506
telemt_user_connections_current{user="hello"} 1184
telemt_user_octets_from_client{user="hello"} 9470866080 (8.82 GB)
telemt_user_octets_to_client{user="hello"} 76048491956 (70.83 GB)
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 25555.5 (7h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2394259
telemt_connections_bad_total 105473
telemt_connections_current 3111
telemt_connections_me_current 3111
telemt_handshake_timeouts_total 45853
telemt_upstream_connect_attempt_total 5458
telemt_upstream_connect_success_total 5383
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 5458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7069
telemt_me_reconnect_success_total 2841
telemt_me_reader_eof_total 3070
telemt_me_idle_close_by_peer_total 3070
telemt_me_route_drop_no_conn_total 1302483
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2023052
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8570
telemt_desync_full_logged_total 2782
telemt_desync_suppressed_total 5788
telemt_desync_frames_bucket_total{bucket="1_2"} 1569
telemt_desync_frames_bucket_total{bucket="3_10"} 3383
telemt_desync_frames_bucket_total{bucket="gt_10"} 3618
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2999
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2786
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 2023043
telemt_user_connections_current{user="hello"} 3112
telemt_user_octets_from_client{user="hello"} 29745859086 (27.70 GB)
telemt_user_octets_to_client{user="hello"} 690398342318 (642.98 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1129
telemt_user_unique_ips_recent_window{user="hello"} 379
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 25533.7 (7h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2166020
telemt_connections_bad_total 254246
telemt_connections_current 2664
telemt_connections_me_current 2664
telemt_handshake_timeouts_total 25623
telemt_upstream_connect_attempt_total 3971
telemt_upstream_connect_success_total 3944
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3550
telemt_me_reconnect_success_total 2631
telemt_me_reader_eof_total 2710
telemt_me_idle_close_by_peer_total 2709
telemt_me_route_drop_no_conn_total 1765142
telemt_me_route_drop_channel_closed_total 157
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1647761
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5876
telemt_desync_full_logged_total 1762
telemt_desync_suppressed_total 4114
telemt_desync_frames_bucket_total{bucket="1_2"} 1481
telemt_desync_frames_bucket_total{bucket="3_10"} 2224
telemt_desync_frames_bucket_total{bucket="gt_10"} 2171
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 55
telemt_me_writer_removed_unexpected_total 2634
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2630
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 1644114
telemt_user_connections_current{user="hello"} 2664
telemt_user_octets_from_client{user="hello"} 23342460536 (21.74 GB)
telemt_user_octets_to_client{user="hello"} 561677019500 (523.10 GB)
telemt_user_unique_ips_current{user="hello"} 862
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 25521.6 (7h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2045017
telemt_connections_bad_total 68422
telemt_connections_current 2386
telemt_connections_me_current 2386
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 26086
telemt_upstream_connect_attempt_total 31203
telemt_upstream_connect_success_total 29675
telemt_upstream_connect_fail_total 1528
telemt_upstream_connect_attempts_per_request{bucket="1"} 31203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1528
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5592
telemt_me_reconnect_success_total 3062
telemt_me_reader_eof_total 3174
telemt_me_idle_close_by_peer_total 3173
telemt_me_route_drop_no_conn_total 1715528
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1755820
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7073
telemt_desync_full_logged_total 2222
telemt_desync_suppressed_total 4851
telemt_desync_frames_bucket_total{bucket="1_2"} 1747
telemt_desync_frames_bucket_total{bucket="3_10"} 2591
telemt_desync_frames_bucket_total{bucket="gt_10"} 2735
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 288
telemt_me_writer_removed_unexpected_total 3515
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3058
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 1780007
telemt_user_connections_current{user="hello"} 2386
telemt_user_octets_from_client{user="hello"} 30234089364 (28.16 GB)
telemt_user_octets_to_client{user="hello"} 409480152790 (381.36 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 812
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 79244.9 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5719551
telemt_connections_bad_total 1017088
telemt_connections_current 2876
telemt_connections_me_current 2876
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 105132
telemt_upstream_connect_attempt_total 65522
telemt_upstream_connect_success_total 63024
telemt_upstream_connect_fail_total 2498
telemt_upstream_connect_attempts_per_request{bucket="1"} 65522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2498
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75301
telemt_me_reconnect_success_total 9888
telemt_me_reader_eof_total 10429
telemt_me_idle_close_by_peer_total 10426
telemt_me_route_drop_no_conn_total 2633121
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4009231
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17654
telemt_desync_full_logged_total 5455
telemt_desync_suppressed_total 12199
telemt_desync_frames_bucket_total{bucket="1_2"} 2953
telemt_desync_frames_bucket_total{bucket="3_10"} 7327
telemt_desync_frames_bucket_total{bucket="gt_10"} 7374
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 10142
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9864
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 4057296
telemt_user_connections_current{user="hello"} 2876
telemt_user_octets_from_client{user="hello"} 63220662971 (58.88 GB)
telemt_user_octets_to_client{user="hello"} 1522736824604 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1020
telemt_user_unique_ips_recent_window{user="hello"} 369
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 25485.1 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557653
telemt_connections_bad_total 42718
telemt_connections_current 643
telemt_connections_me_current 643
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10885
telemt_upstream_connect_attempt_total 7815
telemt_upstream_connect_success_total 7618
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3372
telemt_me_reconnect_success_total 3313
telemt_me_reader_eof_total 3420
telemt_me_idle_close_by_peer_total 3419
telemt_me_route_drop_no_conn_total 378483
telemt_me_route_drop_channel_closed_total 134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442494
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1126
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 769
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 493
telemt_pool_swap_total 18
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 136
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3338
telemt_me_writer_restored_same_endpoint_total 3304
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 461134
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 5229195948 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 97789798206 (91.07 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 25486.1 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1609426
telemt_connections_bad_total 97198
telemt_connections_current 2687
telemt_connections_me_current 2687
telemt_handshake_timeouts_total 26243
telemt_upstream_connect_attempt_total 4228
telemt_upstream_connect_success_total 4197
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 4228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2905
telemt_me_reconnect_success_total 2876
telemt_me_reader_eof_total 3021
telemt_me_idle_close_by_peer_total 3021
telemt_me_route_drop_no_conn_total 610360
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1397373
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7303
telemt_desync_full_logged_total 2267
telemt_desync_suppressed_total 5036
telemt_desync_frames_bucket_total{bucket="1_2"} 1376
telemt_desync_frames_bucket_total{bucket="3_10"} 2538
telemt_desync_frames_bucket_total{bucket="gt_10"} 3389
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2933
telemt_me_writer_restored_same_endpoint_total 2859
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 1396629
telemt_user_connections_current{user="hello"} 2687
telemt_user_octets_from_client{user="hello"} 22588379100 (21.04 GB)
telemt_user_octets_to_client{user="hello"} 650741337416 (606.05 GB)
telemt_user_unique_ips_current{user="hello"} 863
telemt_user_unique_ips_recent_window{user="hello"} 291
```