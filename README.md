# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

# Server Metrics 2026-03-18 15:22:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 24106.0 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901500
telemt_connections_bad_total 69337
telemt_handshake_timeouts_total 25426
telemt_upstream_connect_attempt_total 67392
telemt_upstream_connect_success_total 66419
telemt_upstream_connect_fail_total 973
telemt_upstream_connect_attempts_per_request{bucket="1"} 67392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 973
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 520087
telemt_me_reconnect_success_total 3219
telemt_me_reader_eof_total 3562
telemt_me_idle_close_by_peer_total 3560
telemt_me_route_drop_no_conn_total 485573
telemt_me_route_drop_channel_closed_total 193
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689852
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3147
telemt_desync_full_logged_total 1076
telemt_desync_suppressed_total 2071
telemt_desync_frames_bucket_total{bucket="1_2"} 871
telemt_desync_frames_bucket_total{bucket="3_10"} 1058
telemt_desync_frames_bucket_total{bucket="gt_10"} 1218
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3562
telemt_me_refill_failed_total 16834
telemt_me_writer_restored_same_endpoint_total 3113
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 747921
telemt_user_connections_current{user="hello"} 1736
telemt_user_octets_from_client{user="hello"} 11059460464 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 199028660793 (185.36 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 4674.5 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542005
telemt_connections_bad_total 29242
telemt_connections_current 3424
telemt_connections_me_current 3424
telemt_handshake_timeouts_total 10402
telemt_upstream_connect_attempt_total 802
telemt_upstream_connect_success_total 796
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 508
telemt_me_reconnect_success_total 500
telemt_me_reader_eof_total 407
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 576534
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478441
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1188
telemt_desync_full_logged_total 355
telemt_desync_suppressed_total 833
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 423
telemt_me_writer_restored_same_endpoint_total 498
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 477673
telemt_user_connections_current{user="hello"} 3424
telemt_user_octets_from_client{user="hello"} 4401567756 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 121033492440 (112.72 GB)
telemt_user_unique_ips_current{user="hello"} 1117
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 4602.9 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341234
telemt_connections_bad_total 21199
telemt_connections_current 2831
telemt_connections_me_current 2831
telemt_handshake_timeouts_total 6378
telemt_upstream_connect_attempt_total 615
telemt_upstream_connect_success_total 611
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 328
telemt_me_reconnect_success_total 324
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 207636
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296248
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 924
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 387
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 337
telemt_me_writer_restored_same_endpoint_total 307
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 296225
telemt_user_connections_current{user="hello"} 2830
telemt_user_octets_from_client{user="hello"} 5493084924 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 109170196612 (101.67 GB)
telemt_user_unique_ips_current{user="hello"} 923
telemt_user_unique_ips_recent_window{user="hello"} 396
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 5317.1 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547034
telemt_connections_bad_total 5341
telemt_connections_current 2396
telemt_connections_me_current 2396
telemt_handshake_timeouts_total 7763
telemt_upstream_connect_attempt_total 825
telemt_upstream_connect_success_total 820
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 528
telemt_me_reconnect_success_total 520
telemt_me_reader_eof_total 495
telemt_me_idle_close_by_peer_total 494
telemt_me_route_drop_no_conn_total 1014969
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498762
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1566
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 1178
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 481
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 501
telemt_me_writer_restored_same_endpoint_total 509
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 498734
telemt_user_connections_current{user="hello"} 2396
telemt_user_octets_from_client{user="hello"} 3326156740 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 77445423616 (72.13 GB)
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 319
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 23977.0 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1969807
telemt_connections_bad_total 180408
telemt_handshake_timeouts_total 29888
telemt_upstream_connect_attempt_total 15829
telemt_upstream_connect_success_total 15801
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2987357
telemt_me_reconnect_success_total 2912
telemt_me_reader_eof_total 3049
telemt_me_idle_close_by_peer_total 3049
telemt_me_route_drop_no_conn_total 1989443
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1619068
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4648
telemt_desync_full_logged_total 1637
telemt_desync_suppressed_total 3011
telemt_desync_frames_bucket_total{bucket="1_2"} 759
telemt_desync_frames_bucket_total{bucket="3_10"} 1803
telemt_desync_frames_bucket_total{bucket="gt_10"} 2086
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2989
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2797
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1620849
telemt_user_connections_current{user="hello"} 2858
telemt_user_octets_from_client{user="hello"} 26106947283 (24.31 GB)
telemt_user_octets_to_client{user="hello"} 543622862477 (506.29 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 417
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 4766.7 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101189
telemt_connections_bad_total 5545
telemt_connections_current 885
telemt_connections_me_current 885
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 930
telemt_upstream_connect_attempt_total 4937
telemt_upstream_connect_success_total 4930
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 330273
telemt_me_reconnect_success_total 816
telemt_me_reader_eof_total 737
telemt_me_idle_close_by_peer_total 737
telemt_me_route_drop_no_conn_total 57646
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86418
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 181
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 738
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 805
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 90175
telemt_user_connections_current{user="hello"} 885
telemt_user_octets_from_client{user="hello"} 1536614813 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 16869734181 (15.71 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 3836.5 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265625
telemt_connections_bad_total 11363
telemt_connections_current 2656
telemt_connections_me_current 2656
telemt_handshake_timeouts_total 2465
telemt_upstream_connect_attempt_total 724
telemt_upstream_connect_success_total 724
telemt_upstream_connect_attempts_per_request{bucket="1"} 724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14768
telemt_me_reconnect_success_total 478
telemt_me_reader_eof_total 381
telemt_me_idle_close_by_peer_total 381
telemt_me_route_drop_no_conn_total 190647
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227215
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 530
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 390
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 417
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 227665
telemt_user_connections_current{user="hello"} 2656
telemt_user_octets_from_client{user="hello"} 2533823172 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 87357121824 (81.36 GB)
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 316
```