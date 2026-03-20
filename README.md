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

# Server Metrics 2026-03-20 03:05:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 35302.8 (9h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 651786
telemt_connections_bad_total 41675
telemt_connections_current 862
telemt_connections_me_current 862
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14682
telemt_upstream_connect_attempt_total 7251
telemt_upstream_connect_success_total 7160
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 7251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4304
telemt_me_reconnect_success_total 4264
telemt_me_reader_eof_total 4509
telemt_me_idle_close_by_peer_total 4508
telemt_me_route_drop_no_conn_total 183707
telemt_me_route_drop_channel_closed_total 59
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517690
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2439
telemt_desync_full_logged_total 883
telemt_desync_suppressed_total 1556
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 872
telemt_desync_frames_bucket_total{bucket="gt_10"} 1062
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4301
telemt_me_writer_restored_same_endpoint_total 4251
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 519120
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 30839321684 (28.72 GB)
telemt_user_octets_to_client{user="hello"} 178255858929 (166.01 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 51758.5 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3159803
telemt_connections_bad_total 167726
telemt_connections_current 2104
telemt_connections_me_current 2104
telemt_handshake_timeouts_total 69464
telemt_upstream_connect_attempt_total 10144
telemt_upstream_connect_success_total 9967
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 10144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10406
telemt_me_reconnect_success_total 6159
telemt_me_reader_eof_total 6589
telemt_me_idle_close_by_peer_total 6589
telemt_me_route_drop_no_conn_total 1535895
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2682193
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11471
telemt_desync_full_logged_total 3788
telemt_desync_suppressed_total 7683
telemt_desync_frames_bucket_total{bucket="1_2"} 2203
telemt_desync_frames_bucket_total{bucket="3_10"} 4482
telemt_desync_frames_bucket_total{bucket="gt_10"} 4786
telemt_pool_swap_total 45
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6361
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6104
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 2681931
telemt_user_connections_current{user="hello"} 2104
telemt_user_octets_from_client{user="hello"} 40824601286 (38.02 GB)
telemt_user_octets_to_client{user="hello"} 997430021122 (928.93 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 825
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 51736.5 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3049763
telemt_connections_bad_total 480235
telemt_connections_current 1632
telemt_connections_me_current 1632
telemt_handshake_timeouts_total 48573
telemt_upstream_connect_attempt_total 8466
telemt_upstream_connect_success_total 8405
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6761
telemt_me_reconnect_success_total 5825
telemt_me_reader_eof_total 6122
telemt_me_idle_close_by_peer_total 6121
telemt_me_route_drop_no_conn_total 1947134
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2110152
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7930
telemt_desync_full_logged_total 2424
telemt_desync_suppressed_total 5506
telemt_desync_frames_bucket_total{bucket="1_2"} 1944
telemt_desync_frames_bucket_total{bucket="3_10"} 3005
telemt_desync_frames_bucket_total{bucket="gt_10"} 2981
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 71
telemt_me_writer_removed_unexpected_total 5883
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5824
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2105729
telemt_user_connections_current{user="hello"} 1632
telemt_user_octets_from_client{user="hello"} 32100549160 (29.90 GB)
telemt_user_octets_to_client{user="hello"} 815570843340 (759.56 GB)
telemt_user_unique_ips_current{user="hello"} 640
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 51724.3 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2726173
telemt_connections_bad_total 204364
telemt_connections_current 1409
telemt_connections_me_current 1409
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 32325
telemt_upstream_connect_attempt_total 56348
telemt_upstream_connect_success_total 52037
telemt_upstream_connect_fail_total 4311
telemt_upstream_connect_attempts_per_request{bucket="1"} 56348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4311
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9070
telemt_me_reconnect_success_total 6208
telemt_me_reader_eof_total 6475
telemt_me_idle_close_by_peer_total 6474
telemt_me_route_drop_no_conn_total 1885812
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2211542
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8571
telemt_desync_full_logged_total 2726
telemt_desync_suppressed_total 5845
telemt_desync_frames_bucket_total{bucket="1_2"} 2118
telemt_desync_frames_bucket_total{bucket="3_10"} 3127
telemt_desync_frames_bucket_total{bucket="gt_10"} 3326
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6848
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6204
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 2253631
telemt_user_connections_current{user="hello"} 1409
telemt_user_octets_from_client{user="hello"} 36401285573 (33.90 GB)
telemt_user_octets_to_client{user="hello"} 646105840873 (601.73 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 105447.6 (29h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6383305
telemt_connections_bad_total 1062872
telemt_connections_current 1688
telemt_connections_me_current 1688
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 115310
telemt_upstream_connect_attempt_total 128440
telemt_upstream_connect_success_total 95150
telemt_upstream_connect_fail_total 33290
telemt_upstream_connect_attempts_per_request{bucket="1"} 128440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33290
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79236
telemt_me_reconnect_success_total 13563
telemt_me_reader_eof_total 14601
telemt_me_idle_close_by_peer_total 14587
telemt_me_route_drop_no_conn_total 2823826
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4531943
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
telemt_desync_total 19784
telemt_desync_full_logged_total 6280
telemt_desync_suppressed_total 13504
telemt_desync_frames_bucket_total{bucket="1_2"} 3493
telemt_desync_frames_bucket_total{bucket="3_10"} 8173
telemt_desync_frames_bucket_total{bucket="gt_10"} 8118
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 13877
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13538
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 4607168
telemt_user_connections_current{user="hello"} 1688
telemt_user_octets_from_client{user="hello"} 73337742880 (68.30 GB)
telemt_user_octets_to_client{user="hello"} 1785969036704 (1.62 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 51687.5 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 960339
telemt_connections_bad_total 82994
telemt_connections_current 479
telemt_connections_me_current 479
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13330
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 472612
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_desync_total 1417
telemt_desync_full_logged_total 541
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 811349
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 7740588767 (7.21 GB)
telemt_user_octets_to_client{user="hello"} 146578897510 (136.51 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 51688.8 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2109266
telemt_connections_bad_total 124424
telemt_connections_current 1435
telemt_connections_me_current 1435
telemt_handshake_timeouts_total 39340
telemt_upstream_connect_attempt_total 9335
telemt_upstream_connect_success_total 9272
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 9335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6727
telemt_me_reconnect_success_total 6682
telemt_me_reader_eof_total 7058
telemt_me_idle_close_by_peer_total 7058
telemt_me_route_drop_no_conn_total 764488
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1800016
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9419
telemt_desync_full_logged_total 3036
telemt_desync_suppressed_total 6383
telemt_desync_frames_bucket_total{bucket="1_2"} 1800
telemt_desync_frames_bucket_total{bucket="3_10"} 3298
telemt_desync_frames_bucket_total{bucket="gt_10"} 4321
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6777
telemt_me_writer_restored_same_endpoint_total 6665
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1799116
telemt_user_connections_current{user="hello"} 1435
telemt_user_octets_from_client{user="hello"} 30539635996 (28.44 GB)
telemt_user_octets_to_client{user="hello"} 920639482572 (857.41 GB)
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 138
```