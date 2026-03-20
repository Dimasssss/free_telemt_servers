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

# Server Metrics 2026-03-20 05:38:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 44471.8 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858120
telemt_connections_bad_total 56054
telemt_connections_current 1311
telemt_connections_me_current 1311
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20863
telemt_upstream_connect_attempt_total 8715
telemt_upstream_connect_success_total 8615
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 8715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5327
telemt_me_reconnect_success_total 5284
telemt_me_reader_eof_total 5599
telemt_me_idle_close_by_peer_total 5598
telemt_me_route_drop_no_conn_total 239020
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689949
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3680
telemt_desync_full_logged_total 1325
telemt_desync_suppressed_total 2355
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 1443
telemt_desync_frames_bucket_total{bucket="gt_10"} 1537
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 46
telemt_me_writer_removed_unexpected_total 5337
telemt_me_writer_restored_same_endpoint_total 5271
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 691480
telemt_user_connections_current{user="hello"} 1311
telemt_user_octets_from_client{user="hello"} 33124921504 (30.85 GB)
telemt_user_octets_to_client{user="hello"} 238962248449 (222.55 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 495
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 60927.6 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3808480
telemt_connections_bad_total 339043
telemt_connections_current 4167
telemt_connections_me_current 4167
telemt_handshake_timeouts_total 89217
telemt_upstream_connect_attempt_total 11476
telemt_upstream_connect_success_total 11265
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 11476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11271
telemt_me_reconnect_success_total 7020
telemt_me_reader_eof_total 7513
telemt_me_idle_close_by_peer_total 7512
telemt_me_route_drop_no_conn_total 1698973
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3121896
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12771
telemt_desync_full_logged_total 4268
telemt_desync_suppressed_total 8503
telemt_desync_frames_bucket_total{bucket="1_2"} 2430
telemt_desync_frames_bucket_total{bucket="3_10"} 4951
telemt_desync_frames_bucket_total{bucket="gt_10"} 5390
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 58
telemt_me_writer_removed_unexpected_total 7239
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6965
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 3121623
telemt_user_connections_current{user="hello"} 4167
telemt_user_octets_from_client{user="hello"} 47139081450 (43.90 GB)
telemt_user_octets_to_client{user="hello"} 1186919905082 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1459
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 60905.5 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3446958
telemt_connections_bad_total 498614
telemt_connections_current 2955
telemt_connections_me_current 2955
telemt_handshake_timeouts_total 53610
telemt_upstream_connect_attempt_total 9862
telemt_upstream_connect_success_total 9794
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 9862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7719
telemt_me_reconnect_success_total 6776
telemt_me_reader_eof_total 7141
telemt_me_idle_close_by_peer_total 7140
telemt_me_route_drop_no_conn_total 2064774
telemt_me_route_drop_channel_closed_total 184
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2425478
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8914
telemt_desync_full_logged_total 2759
telemt_desync_suppressed_total 6155
telemt_desync_frames_bucket_total{bucket="1_2"} 2220
telemt_desync_frames_bucket_total{bucket="3_10"} 3389
telemt_desync_frames_bucket_total{bucket="gt_10"} 3305
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 77
telemt_me_writer_removed_unexpected_total 6849
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6775
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 2420522
telemt_user_connections_current{user="hello"} 2955
telemt_user_octets_from_client{user="hello"} 36671248048 (34.15 GB)
telemt_user_octets_to_client{user="hello"} 990489211912 (922.46 GB)
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 375
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 60893.3 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3189864
telemt_connections_bad_total 238912
telemt_connections_current 3199
telemt_connections_me_current 3199
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 46971
telemt_upstream_connect_attempt_total 67237
telemt_upstream_connect_success_total 62531
telemt_upstream_connect_fail_total 4706
telemt_upstream_connect_attempts_per_request{bucket="1"} 67237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 711
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4706
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10073
telemt_me_reconnect_success_total 7105
telemt_me_reader_eof_total 7404
telemt_me_idle_close_by_peer_total 7403
telemt_me_route_drop_no_conn_total 2223431
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2591925
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9677
telemt_desync_full_logged_total 3079
telemt_desync_suppressed_total 6598
telemt_desync_frames_bucket_total{bucket="1_2"} 2297
telemt_desync_frames_bucket_total{bucket="3_10"} 3582
telemt_desync_frames_bucket_total{bucket="gt_10"} 3798
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 674
telemt_me_writer_removed_unexpected_total 7816
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7101
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 2642304
telemt_user_connections_current{user="hello"} 3199
telemt_user_octets_from_client{user="hello"} 40270675752 (37.50 GB)
telemt_user_octets_to_client{user="hello"} 779808350671 (726.25 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1075
telemt_user_unique_ips_recent_window{user="hello"} 445
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 114616.5 (31h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6906584
telemt_connections_bad_total 1206430
telemt_connections_current 3681
telemt_connections_me_current 3681
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 121614
telemt_upstream_connect_attempt_total 129831
telemt_upstream_connect_success_total 96528
telemt_upstream_connect_fail_total 33303
telemt_upstream_connect_attempts_per_request{bucket="1"} 129831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1438
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33303
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80184
telemt_me_reconnect_success_total 14504
telemt_me_reader_eof_total 15607
telemt_me_idle_close_by_peer_total 15593
telemt_me_route_drop_no_conn_total 2975505
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4878800
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
telemt_desync_total 21142
telemt_desync_full_logged_total 6725
telemt_desync_suppressed_total 14417
telemt_desync_frames_bucket_total{bucket="1_2"} 3761
telemt_desync_frames_bucket_total{bucket="3_10"} 8746
telemt_desync_frames_bucket_total{bucket="gt_10"} 8635
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 14837
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14479
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 4953536
telemt_user_connections_current{user="hello"} 3681
telemt_user_octets_from_client{user="hello"} 78694817172 (73.29 GB)
telemt_user_octets_to_client{user="hello"} 1964408904452 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1206
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 60856.5 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1663605
telemt_connections_bad_total 107354
telemt_connections_current 1239
telemt_connections_me_current 1239
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14706
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 60
telemt_me_keepalive_timeout_total 560
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473700
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
telemt_desync_total 1601
telemt_desync_full_logged_total 592
telemt_desync_suppressed_total 1009
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 718
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
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
telemt_user_connections_total{user="hello"} 1479046
telemt_user_connections_current{user="hello"} 1239
telemt_user_octets_from_client{user="hello"} 9284148227 (8.65 GB)
telemt_user_octets_to_client{user="hello"} 146635518070 (136.56 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 60857.8 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2496670
telemt_connections_bad_total 155888
telemt_connections_current 2978
telemt_connections_me_current 2978
telemt_handshake_timeouts_total 45116
telemt_upstream_connect_attempt_total 10882
telemt_upstream_connect_success_total 10815
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7840
telemt_me_reconnect_success_total 7790
telemt_me_reader_eof_total 8234
telemt_me_idle_close_by_peer_total 8234
telemt_me_route_drop_no_conn_total 869827
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2093198
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10580
telemt_desync_full_logged_total 3452
telemt_desync_suppressed_total 7128
telemt_desync_frames_bucket_total{bucket="1_2"} 2060
telemt_desync_frames_bucket_total{bucket="3_10"} 3725
telemt_desync_frames_bucket_total{bucket="gt_10"} 4795
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 7898
telemt_me_writer_restored_same_endpoint_total 7773
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 2091886
telemt_user_connections_current{user="hello"} 2978
telemt_user_octets_from_client{user="hello"} 45259985692 (42.15 GB)
telemt_user_octets_to_client{user="hello"} 1107714851784 (1.01 TB)
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 388
```