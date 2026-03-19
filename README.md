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

# Server Metrics 2026-03-19 21:24:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 14791.7 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372418
telemt_connections_bad_total 18254
telemt_connections_current 863
telemt_connections_me_current 863
telemt_handshake_timeouts_total 5480
telemt_upstream_connect_attempt_total 2368
telemt_upstream_connect_success_total 2345
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1590
telemt_me_reconnect_success_total 1578
telemt_me_reader_eof_total 1665
telemt_me_idle_close_by_peer_total 1665
telemt_me_route_drop_no_conn_total 113648
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295303
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1547
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 328
telemt_desync_frames_bucket_total{bucket="3_10"} 462
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1615
telemt_me_writer_restored_same_endpoint_total 1565
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 295558
telemt_user_connections_current{user="hello"} 863
telemt_user_octets_from_client{user="hello"} 10926942260 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 111611270104 (103.95 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 31247.3 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2667854
telemt_connections_bad_total 113222
telemt_connections_current 2190
telemt_connections_me_current 2190
telemt_handshake_timeouts_total 52086
telemt_upstream_connect_attempt_total 6366
telemt_upstream_connect_success_total 6268
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 6366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7695
telemt_me_reconnect_success_total 3466
telemt_me_reader_eof_total 3732
telemt_me_idle_close_by_peer_total 3732
telemt_me_route_drop_no_conn_total 1408489
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2274400
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10038
telemt_desync_full_logged_total 3273
telemt_desync_suppressed_total 6765
telemt_desync_frames_bucket_total{bucket="1_2"} 1851
telemt_desync_frames_bucket_total{bucket="3_10"} 3937
telemt_desync_frames_bucket_total{bucket="gt_10"} 4250
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 3633
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3411
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2274281
telemt_user_connections_current{user="hello"} 2190
telemt_user_octets_from_client{user="hello"} 35723815142 (33.27 GB)
telemt_user_octets_to_client{user="hello"} 807444593998 (751.99 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 31225.3 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2605479
telemt_connections_bad_total 455524
telemt_connections_current 1520
telemt_connections_me_current 1520
telemt_handshake_timeouts_total 31810
telemt_upstream_connect_attempt_total 4845
telemt_upstream_connect_success_total 4810
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4159
telemt_me_reconnect_success_total 3233
telemt_me_reader_eof_total 3354
telemt_me_idle_close_by_peer_total 3353
telemt_me_route_drop_no_conn_total 1838642
telemt_me_route_drop_channel_closed_total 164
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1824679
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6934
telemt_desync_full_logged_total 2083
telemt_desync_suppressed_total 4851
telemt_desync_frames_bucket_total{bucket="1_2"} 1756
telemt_desync_frames_bucket_total{bucket="3_10"} 2618
telemt_desync_frames_bucket_total{bucket="gt_10"} 2560
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 3251
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3232
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 1820617
telemt_user_connections_current{user="hello"} 1520
telemt_user_octets_from_client{user="hello"} 27042973916 (25.19 GB)
telemt_user_octets_to_client{user="hello"} 657913620168 (612.73 GB)
telemt_user_unique_ips_current{user="hello"} 623
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 31213.0 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2281311
telemt_connections_bad_total 94639
telemt_connections_current 1588
telemt_connections_me_current 1588
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 28427
telemt_upstream_connect_attempt_total 35047
telemt_upstream_connect_success_total 33343
telemt_upstream_connect_fail_total 1704
telemt_upstream_connect_attempts_per_request{bucket="1"} 35047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 441
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1704
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6286
telemt_me_reconnect_success_total 3688
telemt_me_reader_eof_total 3823
telemt_me_idle_close_by_peer_total 3822
telemt_me_route_drop_no_conn_total 1799567
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1943322
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7824
telemt_desync_full_logged_total 2439
telemt_desync_suppressed_total 5385
telemt_desync_frames_bucket_total{bucket="1_2"} 1932
telemt_desync_frames_bucket_total{bucket="3_10"} 2845
telemt_desync_frames_bucket_total{bucket="gt_10"} 3047
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 346
telemt_me_writer_removed_unexpected_total 4191
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3684
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 1970265
telemt_user_connections_current{user="hello"} 1588
telemt_user_octets_from_client{user="hello"} 32702059732 (30.46 GB)
telemt_user_octets_to_client{user="hello"} 489319780387 (455.71 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 84936.2 (23h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5951203
telemt_connections_bad_total 1030139
telemt_connections_current 2110
telemt_connections_me_current 2110
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108047
telemt_upstream_connect_attempt_total 66432
telemt_upstream_connect_success_total 63930
telemt_upstream_connect_fail_total 2502
telemt_upstream_connect_attempts_per_request{bucket="1"} 66432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2502
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75917
telemt_me_reconnect_success_total 10500
telemt_me_reader_eof_total 11085
telemt_me_idle_close_by_peer_total 11082
telemt_me_route_drop_no_conn_total 2719305
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4215042
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
telemt_desync_total 18513
telemt_desync_full_logged_total 5750
telemt_desync_suppressed_total 12763
telemt_desync_frames_bucket_total{bucket="1_2"} 3182
telemt_desync_frames_bucket_total{bucket="3_10"} 7661
telemt_desync_frames_bucket_total{bucket="gt_10"} 7670
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 10762
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10476
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 4263092
telemt_user_connections_current{user="hello"} 2110
telemt_user_octets_from_client{user="hello"} 66304223219 (61.75 GB)
telemt_user_octets_to_client{user="hello"} 1640939821560 (1.49 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 794
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 31176.3 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 610450
telemt_connections_bad_total 48165
telemt_connections_current 520
telemt_connections_me_current 520
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11722
telemt_upstream_connect_attempt_total 8847
telemt_upstream_connect_success_total 8650
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 553
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4146
telemt_me_reconnect_success_total 4083
telemt_me_reader_eof_total 4249
telemt_me_idle_close_by_peer_total 4248
telemt_me_route_drop_no_conn_total 400430
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487887
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
telemt_desync_total 1334
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 842
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 546
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 139
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4120
telemt_me_writer_restored_same_endpoint_total 4074
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 504661
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 6650421312 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 112102878910 (104.40 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 31177.7 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1800274
telemt_connections_bad_total 105375
telemt_connections_current 1802
telemt_connections_me_current 1802
telemt_handshake_timeouts_total 32208
telemt_upstream_connect_attempt_total 5182
telemt_upstream_connect_success_total 5143
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 5182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3591
telemt_me_reconnect_success_total 3557
telemt_me_reader_eof_total 3743
telemt_me_idle_close_by_peer_total 3743
telemt_me_route_drop_no_conn_total 676656
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1564173
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8389
telemt_desync_full_logged_total 2627
telemt_desync_suppressed_total 5762
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 2930
telemt_desync_frames_bucket_total{bucket="gt_10"} 3914
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3625
telemt_me_writer_restored_same_endpoint_total 3540
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1563326
telemt_user_connections_current{user="hello"} 1802
telemt_user_octets_from_client{user="hello"} 26664672392 (24.83 GB)
telemt_user_octets_to_client{user="hello"} 768703514400 (715.91 GB)
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 158
```