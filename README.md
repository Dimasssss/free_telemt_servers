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

# Server Metrics 2026-03-19 22:55:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 20298.8 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442153
telemt_connections_bad_total 27840
telemt_connections_current 769
telemt_connections_me_current 769
telemt_handshake_timeouts_total 6361
telemt_upstream_connect_attempt_total 3366
telemt_upstream_connect_success_total 3338
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2323
telemt_me_reconnect_success_total 2306
telemt_me_reader_eof_total 2446
telemt_me_idle_close_by_peer_total 2446
telemt_me_route_drop_no_conn_total 131076
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350118
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1879
telemt_desync_full_logged_total 663
telemt_desync_suppressed_total 1216
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 883
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2355
telemt_me_writer_restored_same_endpoint_total 2293
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 350388
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 17238786508 (16.05 GB)
telemt_user_octets_to_client{user="hello"} 130287062204 (121.34 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 36754.2 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2824885
telemt_connections_bad_total 120766
telemt_connections_current 1581
telemt_connections_me_current 1581
telemt_handshake_timeouts_total 57379
telemt_upstream_connect_attempt_total 7380
telemt_upstream_connect_success_total 7266
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 7380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8433
telemt_me_reconnect_success_total 4201
telemt_me_reader_eof_total 4512
telemt_me_idle_close_by_peer_total 4512
telemt_me_route_drop_no_conn_total 1453955
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2413414
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10646
telemt_desync_full_logged_total 3496
telemt_desync_suppressed_total 7150
telemt_desync_frames_bucket_total{bucket="1_2"} 1994
telemt_desync_frames_bucket_total{bucket="3_10"} 4164
telemt_desync_frames_bucket_total{bucket="gt_10"} 4488
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 4376
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4146
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 2413292
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 37852195650 (35.25 GB)
telemt_user_octets_to_client{user="hello"} 868029926310 (808.42 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 675
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 36732.1 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2748390
telemt_connections_bad_total 462265
telemt_connections_current 1279
telemt_connections_me_current 1279
telemt_handshake_timeouts_total 35947
telemt_upstream_connect_attempt_total 5752
telemt_upstream_connect_success_total 5706
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 5752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4797
telemt_me_reconnect_success_total 3867
telemt_me_reader_eof_total 4030
telemt_me_idle_close_by_peer_total 4029
telemt_me_route_drop_no_conn_total 1874893
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1915674
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7438
telemt_desync_full_logged_total 2251
telemt_desync_suppressed_total 5187
telemt_desync_frames_bucket_total{bucket="1_2"} 1826
telemt_desync_frames_bucket_total{bucket="3_10"} 2839
telemt_desync_frames_bucket_total{bucket="gt_10"} 2773
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 3897
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3866
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1911476
telemt_user_connections_current{user="hello"} 1279
telemt_user_octets_from_client{user="hello"} 28821787668 (26.84 GB)
telemt_user_octets_to_client{user="hello"} 718735244112 (669.37 GB)
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 36720.2 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2397302
telemt_connections_bad_total 100026
telemt_connections_current 1113
telemt_connections_me_current 1113
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29689
telemt_upstream_connect_attempt_total 36118
telemt_upstream_connect_success_total 34358
telemt_upstream_connect_fail_total 1760
telemt_upstream_connect_attempts_per_request{bucket="1"} 36118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 460
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1760
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7080
telemt_me_reconnect_success_total 4439
telemt_me_reader_eof_total 4606
telemt_me_idle_close_by_peer_total 4605
telemt_me_route_drop_no_conn_total 1835725
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2035813
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8127
telemt_desync_full_logged_total 2562
telemt_desync_suppressed_total 5565
telemt_desync_frames_bucket_total{bucket="1_2"} 1990
telemt_desync_frames_bucket_total{bucket="3_10"} 2954
telemt_desync_frames_bucket_total{bucket="gt_10"} 3183
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4969
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4435
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 2062744
telemt_user_connections_current{user="hello"} 1113
telemt_user_octets_from_client{user="hello"} 33847067752 (31.52 GB)
telemt_user_octets_to_client{user="hello"} 544663491491 (507.26 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 90443.2 (25h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6075220
telemt_connections_bad_total 1036800
telemt_connections_current 1313
telemt_connections_me_current 1313
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 109958
telemt_upstream_connect_attempt_total 67429
telemt_upstream_connect_success_total 64920
telemt_upstream_connect_fail_total 2509
telemt_upstream_connect_attempts_per_request{bucket="1"} 67429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2509
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76648
telemt_me_reconnect_success_total 11229
telemt_me_reader_eof_total 11860
telemt_me_idle_close_by_peer_total 11857
telemt_me_route_drop_no_conn_total 2761762
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4323310
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
telemt_desync_total 19037
telemt_desync_full_logged_total 5938
telemt_desync_suppressed_total 13099
telemt_desync_frames_bucket_total{bucket="1_2"} 3326
telemt_desync_frames_bucket_total{bucket="3_10"} 7813
telemt_desync_frames_bucket_total{bucket="gt_10"} 7898
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 11498
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 11205
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 4371365
telemt_user_connections_current{user="hello"} 1313
telemt_user_octets_from_client{user="hello"} 67756345895 (63.10 GB)
telemt_user_octets_to_client{user="hello"} 1700325541668 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 36683.2 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 644884
telemt_connections_bad_total 51213
telemt_connections_current 349
telemt_connections_me_current 349
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12682
telemt_upstream_connect_attempt_total 10291
telemt_upstream_connect_success_total 10050
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 10291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 591
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4977
telemt_me_reconnect_success_total 4891
telemt_me_reader_eof_total 5106
telemt_me_idle_close_by_peer_total 5104
telemt_me_route_drop_no_conn_total 451569
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546019
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
telemt_desync_total 1372
telemt_desync_full_logged_total 510
telemt_desync_suppressed_total 862
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 561
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 30
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 148
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4936
telemt_me_writer_restored_same_endpoint_total 4882
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 533007
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 7014914261 (6.53 GB)
telemt_user_octets_to_client{user="hello"} 128714927120 (119.88 GB)
telemt_user_msgs_from_client{user="hello"} 8558
telemt_user_msgs_to_client{user="hello"} 13690
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 36684.7 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1907310
telemt_connections_bad_total 114339
telemt_connections_current 1295
telemt_connections_me_current 1295
telemt_handshake_timeouts_total 35540
telemt_upstream_connect_attempt_total 6231
telemt_upstream_connect_success_total 6185
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 6231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4375
telemt_me_reconnect_success_total 4340
telemt_me_reader_eof_total 4571
telemt_me_idle_close_by_peer_total 4571
telemt_me_route_drop_no_conn_total 709619
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1646850
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8805
telemt_desync_full_logged_total 2796
telemt_desync_suppressed_total 6009
telemt_desync_frames_bucket_total{bucket="1_2"} 1610
telemt_desync_frames_bucket_total{bucket="3_10"} 3086
telemt_desync_frames_bucket_total{bucket="gt_10"} 4109
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4414
telemt_me_writer_restored_same_endpoint_total 4323
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1645987
telemt_user_connections_current{user="hello"} 1295
telemt_user_octets_from_client{user="hello"} 27998476876 (26.08 GB)
telemt_user_octets_to_client{user="hello"} 829756810480 (772.77 GB)
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 109
```