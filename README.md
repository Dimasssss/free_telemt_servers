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

# Server Metrics 2026-03-19 05:48:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 28775.2 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426938
telemt_connections_bad_total 41605
telemt_connections_current 1189
telemt_connections_me_current 1189
telemt_handshake_timeouts_total 21515
telemt_upstream_connect_attempt_total 5500
telemt_upstream_connect_success_total 5407
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 5500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4006
telemt_me_reconnect_success_total 3986
telemt_me_reader_eof_total 4203
telemt_me_idle_close_by_peer_total 4202
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 112439
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316639
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2090
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1504
telemt_desync_frames_bucket_total{bucket="1_2"} 745
telemt_desync_frames_bucket_total{bucket="3_10"} 823
telemt_desync_frames_bucket_total{bucket="gt_10"} 522
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4023
telemt_me_writer_restored_same_endpoint_total 3969
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 313891
telemt_user_connections_current{user="hello"} 1189
telemt_user_octets_from_client{user="hello"} 3937628324 (3.67 GB)
telemt_user_octets_to_client{user="hello"} 107076827548 (99.72 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 28779.1 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 876517
telemt_connections_bad_total 51706
telemt_connections_current 3132
telemt_connections_me_current 3132
telemt_handshake_timeouts_total 24871
telemt_upstream_connect_attempt_total 5343
telemt_upstream_connect_success_total 5242
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 5343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 3829
telemt_me_reconnect_success_total 3809
telemt_me_reader_eof_total 4018
telemt_me_idle_close_by_peer_total 4018
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 270555
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 723221
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2913
telemt_desync_full_logged_total 1000
telemt_desync_suppressed_total 1913
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 1091
telemt_desync_frames_bucket_total{bucket="gt_10"} 1273
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3877
telemt_me_writer_restored_same_endpoint_total 3790
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 723103
telemt_user_connections_current{user="hello"} 3132
telemt_user_octets_from_client{user="hello"} 16914454200 (15.75 GB)
telemt_user_octets_to_client{user="hello"} 318025505304 (296.18 GB)
telemt_user_unique_ips_current{user="hello"} 1136
telemt_user_unique_ips_recent_window{user="hello"} 418
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 28776.7 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743409
telemt_connections_bad_total 126190
telemt_connections_current 2607
telemt_connections_me_current 2607
telemt_handshake_timeouts_total 25222
telemt_upstream_connect_attempt_total 5162
telemt_upstream_connect_success_total 5162
telemt_upstream_connect_attempts_per_request{bucket="1"} 5162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3746
telemt_me_reconnect_success_total 3731
telemt_me_reader_eof_total 3955
telemt_me_idle_close_by_peer_total 3955
telemt_me_route_drop_no_conn_total 224749
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538684
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2802
telemt_desync_full_logged_total 908
telemt_desync_suppressed_total 1894
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 1330
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3799
telemt_me_writer_restored_same_endpoint_total 3715
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 538680
telemt_user_connections_current{user="hello"} 2607
telemt_user_octets_from_client{user="hello"} 10590702532 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 322576382812 (300.42 GB)
telemt_user_unique_ips_current{user="hello"} 914
telemt_user_unique_ips_recent_window{user="hello"} 364
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 28829.7 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820866
telemt_connections_bad_total 87390
telemt_connections_current 2233
telemt_connections_me_current 2233
telemt_handshake_timeouts_total 19924
telemt_upstream_connect_attempt_total 5047
telemt_upstream_connect_success_total 5047
telemt_upstream_connect_attempts_per_request{bucket="1"} 5047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 3630
telemt_me_reconnect_success_total 3609
telemt_me_reader_eof_total 3810
telemt_me_idle_close_by_peer_total 3809
telemt_me_route_drop_no_conn_total 241194
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532898
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1793
telemt_desync_full_logged_total 659
telemt_desync_suppressed_total 1134
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 727
telemt_desync_frames_bucket_total{bucket="gt_10"} 733
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3660
telemt_me_writer_restored_same_endpoint_total 3585
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 531818
telemt_user_connections_current{user="hello"} 2233
telemt_user_octets_from_client{user="hello"} 7907527768 (7.36 GB)
telemt_user_octets_to_client{user="hello"} 204735013208 (190.67 GB)
telemt_user_unique_ips_current{user="hello"} 794
telemt_user_unique_ips_recent_window{user="hello"} 325
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 28773.1 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982419
telemt_connections_bad_total 286507
telemt_connections_current 2623
telemt_connections_me_current 2623
telemt_handshake_timeouts_total 26133
telemt_upstream_connect_attempt_total 5118
telemt_upstream_connect_success_total 5087
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 3678
telemt_me_reconnect_success_total 3657
telemt_me_reader_eof_total 3871
telemt_me_idle_close_by_peer_total 3871
telemt_me_route_drop_no_conn_total 234305
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571097
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2792
telemt_desync_full_logged_total 963
telemt_desync_suppressed_total 1829
telemt_desync_frames_bucket_total{bucket="1_2"} 677
telemt_desync_frames_bucket_total{bucket="3_10"} 1203
telemt_desync_frames_bucket_total{bucket="gt_10"} 912
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3696
telemt_me_writer_restored_same_endpoint_total 3633
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 571009
telemt_user_connections_current{user="hello"} 2623
telemt_user_octets_from_client{user="hello"} 15387334400 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 316571325248 (294.83 GB)
telemt_user_unique_ips_current{user="hello"} 951
telemt_user_unique_ips_recent_window{user="hello"} 395
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 28784.5 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166851
telemt_connections_bad_total 11068
telemt_connections_current 646
telemt_connections_me_current 646
telemt_handshake_timeouts_total 1295
telemt_upstream_connect_attempt_total 7877
telemt_upstream_connect_success_total 7670
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 7877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3943
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 10678
telemt_me_reconnect_success_total 6241
telemt_me_reader_eof_total 6607
telemt_me_idle_close_by_peer_total 6607
telemt_me_route_drop_no_conn_total 66772
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145458
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6402
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6211
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 145453
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 2444028452 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 82817922540 (77.13 GB)
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 28775.4 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582791
telemt_connections_bad_total 66952
telemt_connections_current 2470
telemt_connections_me_current 2470
telemt_handshake_timeouts_total 26423
telemt_upstream_connect_attempt_total 5849
telemt_upstream_connect_success_total 5849
telemt_upstream_connect_attempts_per_request{bucket="1"} 5849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4439
telemt_me_reconnect_success_total 4426
telemt_me_reader_eof_total 4671
telemt_me_idle_close_by_peer_total 4671
telemt_me_route_drop_no_conn_total 209939
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471598
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2669
telemt_desync_full_logged_total 962
telemt_desync_suppressed_total 1707
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 1022
telemt_desync_frames_bucket_total{bucket="gt_10"} 1099
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4475
telemt_me_writer_restored_same_endpoint_total 4411
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 471395
telemt_user_connections_current{user="hello"} 2471
telemt_user_octets_from_client{user="hello"} 6141127692 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 275145507820 (256.25 GB)
telemt_user_unique_ips_current{user="hello"} 825
telemt_user_unique_ips_recent_window{user="hello"} 308
```