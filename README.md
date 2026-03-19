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

# Server Metrics 2026-03-19 22:30:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 18770.0 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425301
telemt_connections_bad_total 25563
telemt_connections_current 751
telemt_connections_me_current 751
telemt_handshake_timeouts_total 6098
telemt_upstream_connect_attempt_total 3072
telemt_upstream_connect_success_total 3044
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2117
telemt_me_reconnect_success_total 2100
telemt_me_reader_eof_total 2225
telemt_me_idle_close_by_peer_total 2225
telemt_me_route_drop_no_conn_total 126990
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336753
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1817
telemt_desync_full_logged_total 638
telemt_desync_suppressed_total 1179
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 582
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2146
telemt_me_writer_restored_same_endpoint_total 2087
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 337009
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 12844219372 (11.96 GB)
telemt_user_octets_to_client{user="hello"} 125366998060 (116.76 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 35225.5 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2785997
telemt_connections_bad_total 120086
telemt_connections_current 1585
telemt_connections_me_current 1585
telemt_handshake_timeouts_total 55908
telemt_upstream_connect_attempt_total 7172
telemt_upstream_connect_success_total 7059
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 7172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8269
telemt_me_reconnect_success_total 4038
telemt_me_reader_eof_total 4331
telemt_me_idle_close_by_peer_total 4331
telemt_me_route_drop_no_conn_total 1444224
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2378500
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10545
telemt_desync_full_logged_total 3456
telemt_desync_suppressed_total 7089
telemt_desync_frames_bucket_total{bucket="1_2"} 1968
telemt_desync_frames_bucket_total{bucket="3_10"} 4121
telemt_desync_frames_bucket_total{bucket="gt_10"} 4456
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 4207
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3983
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 2378377
telemt_user_connections_current{user="hello"} 1585
telemt_user_octets_from_client{user="hello"} 37579682994 (35.00 GB)
telemt_user_octets_to_client{user="hello"} 853095958170 (794.51 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 723
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 35203.8 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2712307
telemt_connections_bad_total 460565
telemt_connections_current 1289
telemt_connections_me_current 1289
telemt_handshake_timeouts_total 34860
telemt_upstream_connect_attempt_total 5531
telemt_upstream_connect_success_total 5486
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 5531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4620
telemt_me_reconnect_success_total 3692
telemt_me_reader_eof_total 3841
telemt_me_idle_close_by_peer_total 3840
telemt_me_route_drop_no_conn_total 1865048
telemt_me_route_drop_channel_closed_total 168
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1892817
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7380
telemt_desync_full_logged_total 2227
telemt_desync_suppressed_total 5153
telemt_desync_frames_bucket_total{bucket="1_2"} 1821
telemt_desync_frames_bucket_total{bucket="3_10"} 2820
telemt_desync_frames_bucket_total{bucket="gt_10"} 2739
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 62
telemt_me_writer_removed_unexpected_total 3719
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3691
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1888731
telemt_user_connections_current{user="hello"} 1289
telemt_user_octets_from_client{user="hello"} 28554305216 (26.59 GB)
telemt_user_octets_to_client{user="hello"} 701434110124 (653.26 GB)
telemt_user_unique_ips_current{user="hello"} 536
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 35191.4 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2374081
telemt_connections_bad_total 99368
telemt_connections_current 1266
telemt_connections_me_current 1266
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29454
telemt_upstream_connect_attempt_total 35892
telemt_upstream_connect_success_total 34145
telemt_upstream_connect_fail_total 1747
telemt_upstream_connect_attempts_per_request{bucket="1"} 35892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 455
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1747
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6909
telemt_me_reconnect_success_total 4280
telemt_me_reader_eof_total 4439
telemt_me_idle_close_by_peer_total 4438
telemt_me_route_drop_no_conn_total 1827478
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2016459
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8086
telemt_desync_full_logged_total 2542
telemt_desync_suppressed_total 5544
telemt_desync_frames_bucket_total{bucket="1_2"} 1984
telemt_desync_frames_bucket_total{bucket="3_10"} 2937
telemt_desync_frames_bucket_total{bucket="gt_10"} 3165
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4803
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4276
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 2043390
telemt_user_connections_current{user="hello"} 1266
telemt_user_octets_from_client{user="hello"} 33439267580 (31.14 GB)
telemt_user_octets_to_client{user="hello"} 531979563251 (495.44 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 88914.6 (24h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6049099
telemt_connections_bad_total 1036516
telemt_connections_current 1524
telemt_connections_me_current 1524
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 109426
telemt_upstream_connect_attempt_total 67133
telemt_upstream_connect_success_total 64626
telemt_upstream_connect_fail_total 2507
telemt_upstream_connect_attempts_per_request{bucket="1"} 67133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2507
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76440
telemt_me_reconnect_success_total 11021
telemt_me_reader_eof_total 11638
telemt_me_idle_close_by_peer_total 11635
telemt_me_route_drop_no_conn_total 2751776
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4298922
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
telemt_desync_total 18933
telemt_desync_full_logged_total 5887
telemt_desync_suppressed_total 13046
telemt_desync_frames_bucket_total{bucket="1_2"} 3307
telemt_desync_frames_bucket_total{bucket="3_10"} 7778
telemt_desync_frames_bucket_total{bucket="gt_10"} 7848
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 11288
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10997
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 4346971
telemt_user_connections_current{user="hello"} 1524
telemt_user_octets_from_client{user="hello"} 67339892855 (62.72 GB)
telemt_user_octets_to_client{user="hello"} 1684238938788 (1.53 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 599
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 35154.5 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635310
telemt_connections_bad_total 50097
telemt_connections_current 363
telemt_connections_me_current 363
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12349
telemt_upstream_connect_attempt_total 9631
telemt_upstream_connect_success_total 9418
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 566
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4737
telemt_me_reconnect_success_total 4657
telemt_me_reader_eof_total 4855
telemt_me_idle_close_by_peer_total 4853
telemt_me_route_drop_no_conn_total 448719
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538759
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
telemt_desync_total 1362
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 558
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 147
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4700
telemt_me_writer_restored_same_endpoint_total 4648
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 525422
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 6909846940 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 126687914346 (117.99 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 35155.8 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1881387
telemt_connections_bad_total 109673
telemt_connections_current 1367
telemt_connections_me_current 1367
telemt_handshake_timeouts_total 34888
telemt_upstream_connect_attempt_total 5909
telemt_upstream_connect_success_total 5865
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 5909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4120
telemt_me_reconnect_success_total 4085
telemt_me_reader_eof_total 4299
telemt_me_idle_close_by_peer_total 4299
telemt_me_route_drop_no_conn_total 703009
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1628945
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8703
telemt_desync_full_logged_total 2750
telemt_desync_suppressed_total 5953
telemt_desync_frames_bucket_total{bucket="1_2"} 1600
telemt_desync_frames_bucket_total{bucket="3_10"} 3039
telemt_desync_frames_bucket_total{bucket="gt_10"} 4064
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4159
telemt_me_writer_restored_same_endpoint_total 4068
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1628086
telemt_user_connections_current{user="hello"} 1367
telemt_user_octets_from_client{user="hello"} 27693329544 (25.79 GB)
telemt_user_octets_to_client{user="hello"} 816107242432 (760.06 GB)
telemt_user_unique_ips_current{user="hello"} 523
telemt_user_unique_ips_recent_window{user="hello"} 107
```