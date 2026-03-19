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

# Server Metrics 2026-03-19 22:35:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 19075.7 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428817
telemt_connections_bad_total 26006
telemt_connections_current 758
telemt_connections_me_current 758
telemt_handshake_timeouts_total 6168
telemt_upstream_connect_attempt_total 3152
telemt_upstream_connect_success_total 3124
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2152
telemt_me_reconnect_success_total 2135
telemt_me_reader_eof_total 2265
telemt_me_idle_close_by_peer_total 2265
telemt_me_route_drop_no_conn_total 127997
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339496
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1830
telemt_desync_full_logged_total 645
telemt_desync_suppressed_total 1185
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 590
telemt_desync_frames_bucket_total{bucket="gt_10"} 861
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2181
telemt_me_writer_restored_same_endpoint_total 2122
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 339752
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 13113968012 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 126858233388 (118.15 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 35531.0 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2794593
telemt_connections_bad_total 120102
telemt_connections_current 1676
telemt_connections_me_current 1676
telemt_handshake_timeouts_total 56257
telemt_upstream_connect_attempt_total 7220
telemt_upstream_connect_success_total 7107
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 7220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8317
telemt_me_reconnect_success_total 4086
telemt_me_reader_eof_total 4389
telemt_me_idle_close_by_peer_total 4389
telemt_me_route_drop_no_conn_total 1446471
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2386311
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10569
telemt_desync_full_logged_total 3465
telemt_desync_suppressed_total 7104
telemt_desync_frames_bucket_total{bucket="1_2"} 1976
telemt_desync_frames_bucket_total{bucket="3_10"} 4131
telemt_desync_frames_bucket_total{bucket="gt_10"} 4462
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 4257
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4031
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 2386188
telemt_user_connections_current{user="hello"} 1676
telemt_user_octets_from_client{user="hello"} 37658261538 (35.07 GB)
telemt_user_octets_to_client{user="hello"} 856000704358 (797.21 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 732
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 35509.2 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2719441
telemt_connections_bad_total 460833
telemt_connections_current 1308
telemt_connections_me_current 1308
telemt_handshake_timeouts_total 35073
telemt_upstream_connect_attempt_total 5583
telemt_upstream_connect_success_total 5538
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 5583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4672
telemt_me_reconnect_success_total 3744
telemt_me_reader_eof_total 3899
telemt_me_idle_close_by_peer_total 3898
telemt_me_route_drop_no_conn_total 1867120
telemt_me_route_drop_channel_closed_total 168
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1897649
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7392
telemt_desync_full_logged_total 2232
telemt_desync_suppressed_total 5160
telemt_desync_frames_bucket_total{bucket="1_2"} 1822
telemt_desync_frames_bucket_total{bucket="3_10"} 2824
telemt_desync_frames_bucket_total{bucket="gt_10"} 2746
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 62
telemt_me_writer_removed_unexpected_total 3771
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3743
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1893525
telemt_user_connections_current{user="hello"} 1308
telemt_user_octets_from_client{user="hello"} 28619742516 (26.65 GB)
telemt_user_octets_to_client{user="hello"} 706424274288 (657.91 GB)
telemt_user_unique_ips_current{user="hello"} 524
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 35497.0 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2379000
telemt_connections_bad_total 99477
telemt_connections_current 1266
telemt_connections_me_current 1266
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29499
telemt_upstream_connect_attempt_total 35959
telemt_upstream_connect_success_total 34207
telemt_upstream_connect_fail_total 1752
telemt_upstream_connect_attempts_per_request{bucket="1"} 35959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 457
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1752
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6967
telemt_me_reconnect_success_total 4334
telemt_me_reader_eof_total 4496
telemt_me_idle_close_by_peer_total 4495
telemt_me_route_drop_no_conn_total 1829633
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2020651
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8101
telemt_desync_full_logged_total 2550
telemt_desync_suppressed_total 5551
telemt_desync_frames_bucket_total{bucket="1_2"} 1985
telemt_desync_frames_bucket_total{bucket="3_10"} 2943
telemt_desync_frames_bucket_total{bucket="gt_10"} 3173
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4858
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4330
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 2047582
telemt_user_connections_current{user="hello"} 1266
telemt_user_octets_from_client{user="hello"} 33513947492 (31.21 GB)
telemt_user_octets_to_client{user="hello"} 533887554911 (497.22 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 89220.3 (24h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6054960
telemt_connections_bad_total 1036575
telemt_connections_current 1531
telemt_connections_me_current 1531
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 109535
telemt_upstream_connect_attempt_total 67199
telemt_upstream_connect_success_total 64691
telemt_upstream_connect_fail_total 2508
telemt_upstream_connect_attempts_per_request{bucket="1"} 67199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2508
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76462
telemt_me_reconnect_success_total 11043
telemt_me_reader_eof_total 11660
telemt_me_idle_close_by_peer_total 11657
telemt_me_route_drop_no_conn_total 2754369
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4304443
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
telemt_desync_total 18947
telemt_desync_full_logged_total 5893
telemt_desync_suppressed_total 13054
telemt_desync_frames_bucket_total{bucket="1_2"} 3308
telemt_desync_frames_bucket_total{bucket="3_10"} 7787
telemt_desync_frames_bucket_total{bucket="gt_10"} 7852
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 11310
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 11019
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 4352492
telemt_user_connections_current{user="hello"} 1531
telemt_user_octets_from_client{user="hello"} 67426688163 (62.80 GB)
telemt_user_octets_to_client{user="hello"} 1687840842444 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 608
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 35460.2 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 637903
telemt_connections_bad_total 50228
telemt_connections_current 330
telemt_connections_me_current 330
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12374
telemt_upstream_connect_attempt_total 10072
telemt_upstream_connect_success_total 9831
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 10072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 591
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4804
telemt_me_reconnect_success_total 4718
telemt_me_reader_eof_total 4925
telemt_me_idle_close_by_peer_total 4923
telemt_me_route_drop_no_conn_total 449278
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 540700
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
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 147
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4763
telemt_me_writer_restored_same_endpoint_total 4709
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 527688
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 6929906365 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 126945893564 (118.23 GB)
telemt_user_msgs_from_client{user="hello"} 8558
telemt_user_msgs_to_client{user="hello"} 13690
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 35461.5 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1887496
telemt_connections_bad_total 110796
telemt_connections_current 1372
telemt_connections_me_current 1372
telemt_handshake_timeouts_total 35091
telemt_upstream_connect_attempt_total 6012
telemt_upstream_connect_success_total 5967
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 6012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4200
telemt_me_reconnect_success_total 4164
telemt_me_reader_eof_total 4387
telemt_me_idle_close_by_peer_total 4387
telemt_me_route_drop_no_conn_total 704252
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1632253
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8725
telemt_desync_full_logged_total 2761
telemt_desync_suppressed_total 5964
telemt_desync_frames_bucket_total{bucket="1_2"} 1604
telemt_desync_frames_bucket_total{bucket="3_10"} 3050
telemt_desync_frames_bucket_total{bucket="gt_10"} 4071
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4239
telemt_me_writer_restored_same_endpoint_total 4147
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1631391
telemt_user_connections_current{user="hello"} 1372
telemt_user_octets_from_client{user="hello"} 27736826444 (25.83 GB)
telemt_user_octets_to_client{user="hello"} 819261039736 (763.00 GB)
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 112
```