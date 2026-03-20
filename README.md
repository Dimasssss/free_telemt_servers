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

# Server Metrics 2026-03-20 00:32:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 26118.5 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512569
telemt_connections_bad_total 33087
telemt_connections_current 819
telemt_connections_me_current 819
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7501
telemt_upstream_connect_attempt_total 5610
telemt_upstream_connect_success_total 5535
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 5610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3150
telemt_me_reconnect_success_total 3120
telemt_me_reader_eof_total 3278
telemt_me_idle_close_by_peer_total 3277
telemt_me_route_drop_no_conn_total 150239
telemt_me_route_drop_channel_closed_total 55
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407294
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2015
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1296
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 928
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3137
telemt_me_writer_restored_same_endpoint_total 3107
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 408721
telemt_user_connections_current{user="hello"} 819
telemt_user_octets_from_client{user="hello"} 29264401896 (27.25 GB)
telemt_user_octets_to_client{user="hello"} 147542459473 (137.41 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 42573.8 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2936379
telemt_connections_bad_total 125310
telemt_connections_current 1364
telemt_connections_me_current 1364
telemt_handshake_timeouts_total 63330
telemt_upstream_connect_attempt_total 8577
telemt_upstream_connect_success_total 8436
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 8577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9304
telemt_me_reconnect_success_total 5066
telemt_me_reader_eof_total 5425
telemt_me_idle_close_by_peer_total 5425
telemt_me_route_drop_no_conn_total 1485861
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2511979
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10820
telemt_desync_full_logged_total 3575
telemt_desync_suppressed_total 7245
telemt_desync_frames_bucket_total{bucket="1_2"} 2035
telemt_desync_frames_bucket_total{bucket="3_10"} 4247
telemt_desync_frames_bucket_total{bucket="gt_10"} 4538
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5252
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5011
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 2511795
telemt_user_connections_current{user="hello"} 1364
telemt_user_octets_from_client{user="hello"} 38803538610 (36.14 GB)
telemt_user_octets_to_client{user="hello"} 911015204266 (848.45 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 42551.9 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2868385
telemt_connections_bad_total 469592
telemt_connections_current 1049
telemt_connections_me_current 1049
telemt_handshake_timeouts_total 40407
telemt_upstream_connect_attempt_total 6790
telemt_upstream_connect_success_total 6740
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 6790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5529
telemt_me_reconnect_success_total 4598
telemt_me_reader_eof_total 4815
telemt_me_idle_close_by_peer_total 4814
telemt_me_route_drop_no_conn_total 1902820
telemt_me_route_drop_channel_closed_total 171
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1988361
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7581
telemt_desync_full_logged_total 2292
telemt_desync_suppressed_total 5289
telemt_desync_frames_bucket_total{bucket="1_2"} 1869
telemt_desync_frames_bucket_total{bucket="3_10"} 2886
telemt_desync_frames_bucket_total{bucket="gt_10"} 2826
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 68
telemt_me_writer_removed_unexpected_total 4642
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4597
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1984073
telemt_user_connections_current{user="hello"} 1049
telemt_user_octets_from_client{user="hello"} 29540027496 (27.51 GB)
telemt_user_octets_to_client{user="hello"} 755999050656 (704.08 GB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 42540.0 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2488464
telemt_connections_bad_total 107284
telemt_connections_current 999
telemt_connections_me_current 999
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30421
telemt_upstream_connect_attempt_total 53770
telemt_upstream_connect_success_total 49589
telemt_upstream_connect_fail_total 4181
telemt_upstream_connect_attempts_per_request{bucket="1"} 53770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 522
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4181
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7905
telemt_me_reconnect_success_total 5126
telemt_me_reader_eof_total 5324
telemt_me_idle_close_by_peer_total 5323
telemt_me_route_drop_no_conn_total 1852562
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2092557
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8221
telemt_desync_full_logged_total 2593
telemt_desync_suppressed_total 5628
telemt_desync_frames_bucket_total{bucket="1_2"} 2013
telemt_desync_frames_bucket_total{bucket="3_10"} 2987
telemt_desync_frames_bucket_total{bucket="gt_10"} 3221
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 404
telemt_me_writer_removed_unexpected_total 5708
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5122
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 2133708
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 35098371259 (32.69 GB)
telemt_user_octets_to_client{user="hello"} 597620720139 (556.58 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 96264.0 (26h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6209391
telemt_connections_bad_total 1039492
telemt_connections_current 1218
telemt_connections_me_current 1218
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 111878
telemt_upstream_connect_attempt_total 126695
telemt_upstream_connect_success_total 93412
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 126695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1429
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77974
telemt_me_reconnect_success_total 12307
telemt_me_reader_eof_total 13263
telemt_me_idle_close_by_peer_total 13249
telemt_me_route_drop_no_conn_total 2779953
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4390910
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
telemt_desync_total 19324
telemt_desync_full_logged_total 6107
telemt_desync_suppressed_total 13217
telemt_desync_frames_bucket_total{bucket="1_2"} 3370
telemt_desync_frames_bucket_total{bucket="3_10"} 7938
telemt_desync_frames_bucket_total{bucket="gt_10"} 8016
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 12611
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12282
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 4466125
telemt_user_connections_current{user="hello"} 1218
telemt_user_octets_from_client{user="hello"} 69336884956 (64.58 GB)
telemt_user_octets_to_client{user="hello"} 1723633781296 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 42503.1 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 689968
telemt_connections_bad_total 71001
telemt_connections_current 301
telemt_connections_me_current 301
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12918
telemt_upstream_connect_attempt_total 12820
telemt_upstream_connect_success_total 12490
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6492
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6001
telemt_me_reconnect_success_total 5896
telemt_me_reader_eof_total 6175
telemt_me_idle_close_by_peer_total 6172
telemt_me_route_drop_no_conn_total 462421
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568258
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
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5949
telemt_me_writer_restored_same_endpoint_total 5887
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 556402
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 7157110655 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 136026161162 (126.68 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 42504.4 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1977169
telemt_connections_bad_total 117958
telemt_connections_current 1037
telemt_connections_me_current 1037
telemt_handshake_timeouts_total 36641
telemt_upstream_connect_attempt_total 7468
telemt_upstream_connect_success_total 7412
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 7468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5300
telemt_me_reconnect_success_total 5261
telemt_me_reader_eof_total 5553
telemt_me_idle_close_by_peer_total 5553
telemt_me_route_drop_no_conn_total 731480
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1703946
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9034
telemt_desync_full_logged_total 2896
telemt_desync_suppressed_total 6138
telemt_desync_frames_bucket_total{bucket="1_2"} 1674
telemt_desync_frames_bucket_total{bucket="3_10"} 3184
telemt_desync_frames_bucket_total{bucket="gt_10"} 4176
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5344
telemt_me_writer_restored_same_endpoint_total 5244
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 1703063
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 29339311268 (27.32 GB)
telemt_user_octets_to_client{user="hello"} 864341231592 (804.98 GB)
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 64
```