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

# Server Metrics 2026-03-19 19:18:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 7265.4 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233002
telemt_connections_bad_total 9326
telemt_connections_current 1212
telemt_connections_me_current 1212
telemt_handshake_timeouts_total 2362
telemt_upstream_connect_attempt_total 1077
telemt_upstream_connect_success_total 1063
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 672
telemt_me_reconnect_success_total 667
telemt_me_reader_eof_total 686
telemt_me_idle_close_by_peer_total 686
telemt_me_route_drop_no_conn_total 70371
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180184
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 851
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 573
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 416
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 687
telemt_me_writer_restored_same_endpoint_total 654
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 180439
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 4471278064 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 62515116180 (58.22 GB)
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 23720.8 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2275522
telemt_connections_bad_total 102987
telemt_connections_current 3449
telemt_connections_me_current 3449
telemt_handshake_timeouts_total 43272
telemt_upstream_connect_attempt_total 5202
telemt_upstream_connect_success_total 5133
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 5202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6905
telemt_me_reconnect_success_total 2679
telemt_me_reader_eof_total 2893
telemt_me_idle_close_by_peer_total 2893
telemt_me_route_drop_no_conn_total 1256009
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1913410
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7853
telemt_desync_full_logged_total 2531
telemt_desync_suppressed_total 5322
telemt_desync_frames_bucket_total{bucket="1_2"} 1461
telemt_desync_frames_bucket_total{bucket="3_10"} 3098
telemt_desync_frames_bucket_total{bucket="gt_10"} 3294
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2830
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2624
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 1913418
telemt_user_connections_current{user="hello"} 3449
telemt_user_octets_from_client{user="hello"} 27984015342 (26.06 GB)
telemt_user_octets_to_client{user="hello"} 640702781758 (596.70 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1217
telemt_user_unique_ips_recent_window{user="hello"} 434
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 23699.0 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2065901
telemt_connections_bad_total 246641
telemt_connections_current 2653
telemt_connections_me_current 2653
telemt_handshake_timeouts_total 24074
telemt_upstream_connect_attempt_total 3707
telemt_upstream_connect_success_total 3682
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3375
telemt_me_reconnect_success_total 2457
telemt_me_reader_eof_total 2523
telemt_me_idle_close_by_peer_total 2522
telemt_me_route_drop_no_conn_total 1737215
telemt_me_route_drop_channel_closed_total 151
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1571424
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5498
telemt_desync_full_logged_total 1634
telemt_desync_suppressed_total 3864
telemt_desync_frames_bucket_total{bucket="1_2"} 1388
telemt_desync_frames_bucket_total{bucket="3_10"} 2079
telemt_desync_frames_bucket_total{bucket="gt_10"} 2031
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 54
telemt_me_writer_removed_unexpected_total 2457
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2456
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1567787
telemt_user_connections_current{user="hello"} 2653
telemt_user_octets_from_client{user="hello"} 21094524948 (19.65 GB)
telemt_user_octets_to_client{user="hello"} 525358203908 (489.28 GB)
telemt_user_unique_ips_current{user="hello"} 902
telemt_user_unique_ips_recent_window{user="hello"} 323
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 23686.7 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1939681
telemt_connections_bad_total 63811
telemt_connections_current 2595
telemt_connections_me_current 2595
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 24965
telemt_upstream_connect_attempt_total 25768
telemt_upstream_connect_success_total 24563
telemt_upstream_connect_fail_total 1205
telemt_upstream_connect_attempts_per_request{bucket="1"} 25768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1205
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5300
telemt_me_reconnect_success_total 2912
telemt_me_reader_eof_total 3022
telemt_me_idle_close_by_peer_total 3021
telemt_me_route_drop_no_conn_total 1670705
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1674362
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6697
telemt_desync_full_logged_total 2069
telemt_desync_suppressed_total 4628
telemt_desync_frames_bucket_total{bucket="1_2"} 1697
telemt_desync_frames_bucket_total{bucket="3_10"} 2455
telemt_desync_frames_bucket_total{bucket="gt_10"} 2545
telemt_pool_swap_total 11
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3328
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2908
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 1693687
telemt_user_connections_current{user="hello"} 2595
telemt_user_octets_from_client{user="hello"} 28517511629 (26.56 GB)
telemt_user_octets_to_client{user="hello"} 381152310081 (354.98 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 910
telemt_user_unique_ips_recent_window{user="hello"} 352
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 77409.8 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5626903
telemt_connections_bad_total 1014540
telemt_connections_current 3126
telemt_connections_me_current 3126
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 102879
telemt_upstream_connect_attempt_total 65249
telemt_upstream_connect_success_total 62753
telemt_upstream_connect_fail_total 2496
telemt_upstream_connect_attempts_per_request{bucket="1"} 65249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1050
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2496
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75128
telemt_me_reconnect_success_total 9717
telemt_me_reader_eof_total 10249
telemt_me_idle_close_by_peer_total 10246
telemt_me_route_drop_no_conn_total 2575351
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3927873
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
telemt_desync_total 17334
telemt_desync_full_logged_total 5319
telemt_desync_suppressed_total 12015
telemt_desync_frames_bucket_total{bucket="1_2"} 2901
telemt_desync_frames_bucket_total{bucket="3_10"} 7182
telemt_desync_frames_bucket_total{bucket="gt_10"} 7251
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 9968
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9693
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 3975987
telemt_user_connections_current{user="hello"} 3126
telemt_user_octets_from_client{user="hello"} 62047658387 (57.79 GB)
telemt_user_octets_to_client{user="hello"} 1475007224036 (1.34 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 405
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 23651.2 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533510
telemt_connections_bad_total 38377
telemt_connections_current 689
telemt_connections_me_current 689
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10734
telemt_upstream_connect_attempt_total 7512
telemt_upstream_connect_success_total 7315
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3156
telemt_me_reconnect_success_total 3099
telemt_me_reader_eof_total 3192
telemt_me_idle_close_by_peer_total 3191
telemt_me_route_drop_no_conn_total 369654
telemt_me_route_drop_channel_closed_total 132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423578
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
telemt_desync_total 1117
telemt_desync_full_logged_total 353
telemt_desync_suppressed_total 764
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 134
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3123
telemt_me_writer_restored_same_endpoint_total 3090
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 442220
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 5070176816 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 92596641286 (86.24 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 23651.3 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1522202
telemt_connections_bad_total 90477
telemt_connections_current 2922
telemt_connections_me_current 2922
telemt_handshake_timeouts_total 25366
telemt_upstream_connect_attempt_total 3905
telemt_upstream_connect_success_total 3875
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2671
telemt_me_reconnect_success_total 2642
telemt_me_reader_eof_total 2774
telemt_me_idle_close_by_peer_total 2774
telemt_me_route_drop_no_conn_total 583329
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1322863
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6984
telemt_desync_full_logged_total 2150
telemt_desync_suppressed_total 4834
telemt_desync_frames_bucket_total{bucket="1_2"} 1329
telemt_desync_frames_bucket_total{bucket="3_10"} 2424
telemt_desync_frames_bucket_total{bucket="gt_10"} 3231
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2697
telemt_me_writer_restored_same_endpoint_total 2625
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1322113
telemt_user_connections_current{user="hello"} 2922
telemt_user_octets_from_client{user="hello"} 21181685956 (19.73 GB)
telemt_user_octets_to_client{user="hello"} 599377126564 (558.21 GB)
telemt_user_unique_ips_current{user="hello"} 928
telemt_user_unique_ips_recent_window{user="hello"} 362
```