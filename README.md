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

# Server Metrics 2026-03-20 01:23:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 29181.7 (8h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551824
telemt_connections_bad_total 35812
telemt_connections_current 717
telemt_connections_me_current 717
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8051
telemt_upstream_connect_attempt_total 6229
telemt_upstream_connect_success_total 6148
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 6229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3593
telemt_me_reconnect_success_total 3558
telemt_me_reader_eof_total 3752
telemt_me_idle_close_by_peer_total 3751
telemt_me_route_drop_no_conn_total 160642
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440528
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2095
telemt_desync_full_logged_total 753
telemt_desync_suppressed_total 1342
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 953
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3581
telemt_me_writer_restored_same_endpoint_total 3545
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 441958
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 29666960300 (27.63 GB)
telemt_user_octets_to_client{user="hello"} 158268081537 (147.40 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 45636.3 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2985836
telemt_connections_bad_total 125802
telemt_connections_current 1395
telemt_connections_me_current 1395
telemt_handshake_timeouts_total 65530
telemt_upstream_connect_attempt_total 9103
telemt_upstream_connect_success_total 8950
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 9103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9690
telemt_me_reconnect_success_total 5449
telemt_me_reader_eof_total 5831
telemt_me_idle_close_by_peer_total 5831
telemt_me_route_drop_no_conn_total 1499197
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2557740
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11072
telemt_desync_full_logged_total 3645
telemt_desync_suppressed_total 7427
telemt_desync_frames_bucket_total{bucket="1_2"} 2122
telemt_desync_frames_bucket_total{bucket="3_10"} 4336
telemt_desync_frames_bucket_total{bucket="gt_10"} 4614
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5641
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5394
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 2557521
telemt_user_connections_current{user="hello"} 1395
telemt_user_octets_from_client{user="hello"} 39200840982 (36.51 GB)
telemt_user_octets_to_client{user="hello"} 934210717854 (870.05 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 625
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 45614.2 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2932264
telemt_connections_bad_total 472785
telemt_connections_current 1123
telemt_connections_me_current 1123
telemt_handshake_timeouts_total 42583
telemt_upstream_connect_attempt_total 7337
telemt_upstream_connect_success_total 7283
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 7337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5940
telemt_me_reconnect_success_total 5007
telemt_me_reader_eof_total 5251
telemt_me_idle_close_by_peer_total 5250
telemt_me_route_drop_no_conn_total 1916059
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2024291
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7626
telemt_desync_full_logged_total 2312
telemt_desync_suppressed_total 5314
telemt_desync_frames_bucket_total{bucket="1_2"} 1880
telemt_desync_frames_bucket_total{bucket="3_10"} 2906
telemt_desync_frames_bucket_total{bucket="gt_10"} 2840
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 5057
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5006
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2019935
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 29867053404 (27.82 GB)
telemt_user_octets_to_client{user="hello"} 770713126792 (717.78 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 45602.1 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2546652
telemt_connections_bad_total 122208
telemt_connections_current 1047
telemt_connections_me_current 1047
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31057
telemt_upstream_connect_attempt_total 55290
telemt_upstream_connect_success_total 51018
telemt_upstream_connect_fail_total 4272
telemt_upstream_connect_attempts_per_request{bucket="1"} 55290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7418
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4272
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8333
telemt_me_reconnect_success_total 5497
telemt_me_reader_eof_total 5708
telemt_me_idle_close_by_peer_total 5707
telemt_me_route_drop_no_conn_total 1861255
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2127783
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8300
telemt_desync_full_logged_total 2621
telemt_desync_suppressed_total 5679
telemt_desync_frames_bucket_total{bucket="1_2"} 2045
telemt_desync_frames_bucket_total{bucket="3_10"} 3017
telemt_desync_frames_bucket_total{bucket="gt_10"} 3238
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 476
telemt_me_writer_removed_unexpected_total 6119
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5493
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 2169854
telemt_user_connections_current{user="hello"} 1047
telemt_user_octets_from_client{user="hello"} 35431065781 (33.00 GB)
telemt_user_octets_to_client{user="hello"} 608705061873 (566.90 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 99325.4 (27h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6256303
telemt_connections_bad_total 1041855
telemt_connections_current 1166
telemt_connections_me_current 1166
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113179
telemt_upstream_connect_attempt_total 127301
telemt_upstream_connect_success_total 94018
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 127301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78406
telemt_me_reconnect_success_total 12736
telemt_me_reader_eof_total 13720
telemt_me_idle_close_by_peer_total 13706
telemt_me_route_drop_no_conn_total 2793329
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4431928
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
telemt_desync_total 19492
telemt_desync_full_logged_total 6170
telemt_desync_suppressed_total 13322
telemt_desync_frames_bucket_total{bucket="1_2"} 3429
telemt_desync_frames_bucket_total{bucket="3_10"} 8022
telemt_desync_frames_bucket_total{bucket="gt_10"} 8041
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 13042
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12711
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 4507142
telemt_user_connections_current{user="hello"} 1166
telemt_user_octets_from_client{user="hello"} 70973458376 (66.10 GB)
telemt_user_octets_to_client{user="hello"} 1736561290280 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 497
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 45565.5 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706140
telemt_connections_bad_total 74911
telemt_connections_current 364
telemt_connections_me_current 364
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13000
telemt_upstream_connect_attempt_total 13468
telemt_upstream_connect_success_total 13138
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6520
telemt_me_reconnect_success_total 6413
telemt_me_reader_eof_total 6728
telemt_me_idle_close_by_peer_total 6725
telemt_me_route_drop_no_conn_total 467960
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580083
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
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6474
telemt_me_writer_restored_same_endpoint_total 6404
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 568229
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 7309852075 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 143811034526 (133.93 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 45566.9 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2009043
telemt_connections_bad_total 119972
telemt_connections_current 1171
telemt_connections_me_current 1171
telemt_handshake_timeouts_total 37323
telemt_upstream_connect_attempt_total 8097
telemt_upstream_connect_success_total 8038
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 8097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5797
telemt_me_reconnect_success_total 5756
telemt_me_reader_eof_total 6074
telemt_me_idle_close_by_peer_total 6074
telemt_me_route_drop_no_conn_total 740303
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1731815
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9154
telemt_desync_full_logged_total 2944
telemt_desync_suppressed_total 6210
telemt_desync_frames_bucket_total{bucket="1_2"} 1714
telemt_desync_frames_bucket_total{bucket="3_10"} 3211
telemt_desync_frames_bucket_total{bucket="gt_10"} 4229
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 5843
telemt_me_writer_restored_same_endpoint_total 5739
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 1730924
telemt_user_connections_current{user="hello"} 1171
telemt_user_octets_from_client{user="hello"} 29585501720 (27.55 GB)
telemt_user_octets_to_client{user="hello"} 877141082852 (816.90 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 85
```