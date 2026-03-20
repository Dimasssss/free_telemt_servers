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

# Server Metrics 2026-03-20 00:12:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 24894.8 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496980
telemt_connections_bad_total 32140
telemt_connections_current 799
telemt_connections_me_current 799
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7405
telemt_upstream_connect_attempt_total 5412
telemt_upstream_connect_success_total 5340
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 5412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2998
telemt_me_reconnect_success_total 2969
telemt_me_reader_eof_total 3120
telemt_me_idle_close_by_peer_total 3119
telemt_me_route_drop_no_conn_total 145697
telemt_me_route_drop_channel_closed_total 55
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393920
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2001
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1295
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 925
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 2986
telemt_me_writer_restored_same_endpoint_total 2956
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 395329
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 29151707724 (27.15 GB)
telemt_user_octets_to_client{user="hello"} 143766688833 (133.89 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 41349.4 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2914252
telemt_connections_bad_total 123658
telemt_connections_current 1387
telemt_connections_me_current 1387
telemt_handshake_timeouts_total 62204
telemt_upstream_connect_attempt_total 8202
telemt_upstream_connect_success_total 8069
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 8202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9023
telemt_me_reconnect_success_total 4786
telemt_me_reader_eof_total 5129
telemt_me_idle_close_by_peer_total 5129
telemt_me_route_drop_no_conn_total 1479845
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2493119
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10786
telemt_desync_full_logged_total 3567
telemt_desync_suppressed_total 7219
telemt_desync_frames_bucket_total{bucket="1_2"} 2025
telemt_desync_frames_bucket_total{bucket="3_10"} 4234
telemt_desync_frames_bucket_total{bucket="gt_10"} 4527
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 4970
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4731
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 2492942
telemt_user_connections_current{user="hello"} 1387
telemt_user_octets_from_client{user="hello"} 38645493878 (35.99 GB)
telemt_user_octets_to_client{user="hello"} 902993027158 (840.98 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 41327.6 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2843460
telemt_connections_bad_total 468508
telemt_connections_current 1144
telemt_connections_me_current 1144
telemt_handshake_timeouts_total 39004
telemt_upstream_connect_attempt_total 6542
telemt_upstream_connect_success_total 6493
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 6542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5368
telemt_me_reconnect_success_total 4437
telemt_me_reader_eof_total 4638
telemt_me_idle_close_by_peer_total 4637
telemt_me_route_drop_no_conn_total 1896870
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1973856
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7530
telemt_desync_full_logged_total 2278
telemt_desync_suppressed_total 5252
telemt_desync_frames_bucket_total{bucket="1_2"} 1852
telemt_desync_frames_bucket_total{bucket="3_10"} 2863
telemt_desync_frames_bucket_total{bucket="gt_10"} 2815
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 65
telemt_me_writer_removed_unexpected_total 4479
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4436
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 1969601
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 29431975096 (27.41 GB)
telemt_user_octets_to_client{user="hello"} 748179797752 (696.80 GB)
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 41315.6 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2474283
telemt_connections_bad_total 107224
telemt_connections_current 1032
telemt_connections_me_current 1032
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30326
telemt_upstream_connect_attempt_total 53525
telemt_upstream_connect_success_total 49354
telemt_upstream_connect_fail_total 4171
telemt_upstream_connect_attempts_per_request{bucket="1"} 53525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4171
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7747
telemt_me_reconnect_success_total 4977
telemt_me_reader_eof_total 5162
telemt_me_idle_close_by_peer_total 5161
telemt_me_route_drop_no_conn_total 1848140
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2080707
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8195
telemt_desync_full_logged_total 2585
telemt_desync_suppressed_total 5610
telemt_desync_frames_bucket_total{bucket="1_2"} 2010
telemt_desync_frames_bucket_total{bucket="3_10"} 2980
telemt_desync_frames_bucket_total{bucket="gt_10"} 3205
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 404
telemt_me_writer_removed_unexpected_total 5554
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4973
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 2121858
telemt_user_connections_current{user="hello"} 1032
telemt_user_octets_from_client{user="hello"} 34920021723 (32.52 GB)
telemt_user_octets_to_client{user="hello"} 584495160207 (544.35 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 95038.8 (26h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6191238
telemt_connections_bad_total 1038475
telemt_connections_current 1256
telemt_connections_me_current 1256
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 111388
telemt_upstream_connect_attempt_total 126526
telemt_upstream_connect_success_total 93244
telemt_upstream_connect_fail_total 33282
telemt_upstream_connect_attempts_per_request{bucket="1"} 126526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33282
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77849
telemt_me_reconnect_success_total 12184
telemt_me_reader_eof_total 13135
telemt_me_idle_close_by_peer_total 13121
telemt_me_route_drop_no_conn_total 2775650
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4374842
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
telemt_desync_total 19220
telemt_desync_full_logged_total 6056
telemt_desync_suppressed_total 13164
telemt_desync_frames_bucket_total{bucket="1_2"} 3361
telemt_desync_frames_bucket_total{bucket="3_10"} 7889
telemt_desync_frames_bucket_total{bucket="gt_10"} 7970
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 12487
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12159
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 4450057
telemt_user_connections_current{user="hello"} 1256
telemt_user_octets_from_client{user="hello"} 68630443264 (63.92 GB)
telemt_user_octets_to_client{user="hello"} 1717480968132 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 41278.6 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684147
telemt_connections_bad_total 69907
telemt_connections_current 312
telemt_connections_me_current 312
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12893
telemt_upstream_connect_attempt_total 12495
telemt_upstream_connect_success_total 12165
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5762
telemt_me_reconnect_success_total 5657
telemt_me_reader_eof_total 5908
telemt_me_idle_close_by_peer_total 5905
telemt_me_route_drop_no_conn_total 459907
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563848
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5708
telemt_me_writer_restored_same_endpoint_total 5648
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 551992
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 7131313063 (6.64 GB)
telemt_user_octets_to_client{user="hello"} 134300582554 (125.08 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 41280.0 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1964784
telemt_connections_bad_total 117951
telemt_connections_current 1112
telemt_connections_me_current 1112
telemt_handshake_timeouts_total 36455
telemt_upstream_connect_attempt_total 7215
telemt_upstream_connect_success_total 7161
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 7215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5135
telemt_me_reconnect_success_total 5097
telemt_me_reader_eof_total 5376
telemt_me_idle_close_by_peer_total 5376
telemt_me_route_drop_no_conn_total 727542
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1692311
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8998
telemt_desync_full_logged_total 2879
telemt_desync_suppressed_total 6119
telemt_desync_frames_bucket_total{bucket="1_2"} 1659
telemt_desync_frames_bucket_total{bucket="3_10"} 3168
telemt_desync_frames_bucket_total{bucket="gt_10"} 4171
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5178
telemt_me_writer_restored_same_endpoint_total 5080
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1691442
telemt_user_connections_current{user="hello"} 1112
telemt_user_octets_from_client{user="hello"} 29185509120 (27.18 GB)
telemt_user_octets_to_client{user="hello"} 859235556804 (800.23 GB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 82
```