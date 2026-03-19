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

# Server Metrics 2026-03-19 21:19:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 14486.5 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368332
telemt_connections_bad_total 17982
telemt_connections_current 883
telemt_connections_me_current 883
telemt_handshake_timeouts_total 5446
telemt_upstream_connect_attempt_total 2293
telemt_upstream_connect_success_total 2271
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1523
telemt_me_reconnect_success_total 1513
telemt_me_reader_eof_total 1595
telemt_me_idle_close_by_peer_total 1595
telemt_me_route_drop_no_conn_total 112193
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291711
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1515
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 983
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 449
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1549
telemt_me_writer_restored_same_endpoint_total 1500
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 291966
telemt_user_connections_current{user="hello"} 883
telemt_user_octets_from_client{user="hello"} 10894773060 (10.15 GB)
telemt_user_octets_to_client{user="hello"} 108903548820 (101.42 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 30941.5 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2657154
telemt_connections_bad_total 112767
telemt_connections_current 2272
telemt_connections_me_current 2272
telemt_handshake_timeouts_total 51750
telemt_upstream_connect_attempt_total 6333
telemt_upstream_connect_success_total 6235
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 6333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7662
telemt_me_reconnect_success_total 3434
telemt_me_reader_eof_total 3700
telemt_me_idle_close_by_peer_total 3700
telemt_me_route_drop_no_conn_total 1404749
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2264667
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9946
telemt_desync_full_logged_total 3249
telemt_desync_suppressed_total 6697
telemt_desync_frames_bucket_total{bucket="1_2"} 1836
telemt_desync_frames_bucket_total{bucket="3_10"} 3899
telemt_desync_frames_bucket_total{bucket="gt_10"} 4211
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 3601
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3379
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2264549
telemt_user_connections_current{user="hello"} 2272
telemt_user_octets_from_client{user="hello"} 35199201390 (32.78 GB)
telemt_user_octets_to_client{user="hello"} 803884537170 (748.68 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 879
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 30919.8 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2595017
telemt_connections_bad_total 455142
telemt_connections_current 1583
telemt_connections_me_current 1583
telemt_handshake_timeouts_total 31307
telemt_upstream_connect_attempt_total 4818
telemt_upstream_connect_success_total 4783
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4132
telemt_me_reconnect_success_total 3207
telemt_me_reader_eof_total 3326
telemt_me_idle_close_by_peer_total 3325
telemt_me_route_drop_no_conn_total 1836279
telemt_me_route_drop_channel_closed_total 164
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1818517
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6888
telemt_desync_full_logged_total 2066
telemt_desync_suppressed_total 4822
telemt_desync_frames_bucket_total{bucket="1_2"} 1746
telemt_desync_frames_bucket_total{bucket="3_10"} 2594
telemt_desync_frames_bucket_total{bucket="gt_10"} 2548
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 3223
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3206
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1814455
telemt_user_connections_current{user="hello"} 1583
telemt_user_octets_from_client{user="hello"} 26486565144 (24.67 GB)
telemt_user_octets_to_client{user="hello"} 654532193092 (609.58 GB)
telemt_user_unique_ips_current{user="hello"} 647
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 30907.6 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2272542
telemt_connections_bad_total 94484
telemt_connections_current 1548
telemt_connections_me_current 1548
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 28259
telemt_upstream_connect_attempt_total 35018
telemt_upstream_connect_success_total 33316
telemt_upstream_connect_fail_total 1702
telemt_upstream_connect_attempts_per_request{bucket="1"} 35018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 441
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1702
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6257
telemt_me_reconnect_success_total 3662
telemt_me_reader_eof_total 3797
telemt_me_idle_close_by_peer_total 3796
telemt_me_route_drop_no_conn_total 1797580
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1935735
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7796
telemt_desync_full_logged_total 2431
telemt_desync_suppressed_total 5365
telemt_desync_frames_bucket_total{bucket="1_2"} 1932
telemt_desync_frames_bucket_total{bucket="3_10"} 2828
telemt_desync_frames_bucket_total{bucket="gt_10"} 3036
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 346
telemt_me_writer_removed_unexpected_total 4163
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3658
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 501
telemt_user_connections_total{user="hello"} 1962680
telemt_user_connections_current{user="hello"} 1548
telemt_user_octets_from_client{user="hello"} 32567600836 (30.33 GB)
telemt_user_octets_to_client{user="hello"} 486364776287 (452.96 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 594
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 84630.7 (23h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5942489
telemt_connections_bad_total 1030082
telemt_connections_current 2214
telemt_connections_me_current 2214
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 107969
telemt_upstream_connect_attempt_total 66334
telemt_upstream_connect_success_total 63833
telemt_upstream_connect_fail_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 66334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75858
telemt_me_reconnect_success_total 10442
telemt_me_reader_eof_total 11023
telemt_me_idle_close_by_peer_total 11020
telemt_me_route_drop_no_conn_total 2716356
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4206887
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
telemt_desync_total 18484
telemt_desync_full_logged_total 5738
telemt_desync_suppressed_total 12746
telemt_desync_frames_bucket_total{bucket="1_2"} 3172
telemt_desync_frames_bucket_total{bucket="3_10"} 7650
telemt_desync_frames_bucket_total{bucket="gt_10"} 7662
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 10704
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10418
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 4254938
telemt_user_connections_current{user="hello"} 2214
telemt_user_octets_from_client{user="hello"} 66199485091 (61.65 GB)
telemt_user_octets_to_client{user="hello"} 1633885927596 (1.49 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 30870.7 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608361
telemt_connections_bad_total 47999
telemt_connections_current 498
telemt_connections_me_current 498
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11694
telemt_upstream_connect_attempt_total 8812
telemt_upstream_connect_success_total 8615
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 553
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4111
telemt_me_reconnect_success_total 4048
telemt_me_reader_eof_total 4212
telemt_me_idle_close_by_peer_total 4211
telemt_me_route_drop_no_conn_total 399387
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485946
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
telemt_desync_total 1330
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 842
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 578
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 139
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4083
telemt_me_writer_restored_same_endpoint_total 4039
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 502892
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 6633599772 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 111277444066 (103.64 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 30872.2 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1791975
telemt_connections_bad_total 105211
telemt_connections_current 1925
telemt_connections_me_current 1925
telemt_handshake_timeouts_total 31912
telemt_upstream_connect_attempt_total 5161
telemt_upstream_connect_success_total 5122
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 5161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3570
telemt_me_reconnect_success_total 3536
telemt_me_reader_eof_total 3719
telemt_me_idle_close_by_peer_total 3719
telemt_me_route_drop_no_conn_total 674351
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1557011
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8358
telemt_desync_full_logged_total 2611
telemt_desync_suppressed_total 5747
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 2921
telemt_desync_frames_bucket_total{bucket="gt_10"} 3892
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3601
telemt_me_writer_restored_same_endpoint_total 3519
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 1556164
telemt_user_connections_current{user="hello"} 1925
telemt_user_octets_from_client{user="hello"} 26565052952 (24.74 GB)
telemt_user_octets_to_client{user="hello"} 762679843288 (710.30 GB)
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 184
```