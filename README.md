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

# Server Metrics 2026-03-19 06:03:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 29694.8 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451178
telemt_connections_bad_total 44198
telemt_connections_current 1228
telemt_connections_me_current 1228
telemt_handshake_timeouts_total 21812
telemt_upstream_connect_attempt_total 5754
telemt_upstream_connect_success_total 5655
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 5754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4209
telemt_me_reconnect_success_total 4188
telemt_me_reader_eof_total 4407
telemt_me_idle_close_by_peer_total 4406
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 118591
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335527
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2171
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1554
telemt_desync_frames_bucket_total{bucket="1_2"} 759
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 558
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4227
telemt_me_writer_restored_same_endpoint_total 4171
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 332778
telemt_user_connections_current{user="hello"} 1228
telemt_user_octets_from_client{user="hello"} 4144155152 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 114628402560 (106.76 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 29698.2 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940036
telemt_connections_bad_total 55315
telemt_connections_current 3403
telemt_connections_me_current 3403
telemt_handshake_timeouts_total 26956
telemt_upstream_connect_attempt_total 5583
telemt_upstream_connect_success_total 5482
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 5583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 4023
telemt_me_reconnect_success_total 3998
telemt_me_reader_eof_total 4209
telemt_me_idle_close_by_peer_total 4209
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 292786
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772135
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3178
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 2092
telemt_desync_frames_bucket_total{bucket="1_2"} 585
telemt_desync_frames_bucket_total{bucket="3_10"} 1192
telemt_desync_frames_bucket_total{bucket="gt_10"} 1401
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4070
telemt_me_writer_restored_same_endpoint_total 3978
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 772028
telemt_user_connections_current{user="hello"} 3403
telemt_user_octets_from_client{user="hello"} 17560622848 (16.35 GB)
telemt_user_octets_to_client{user="hello"} 341985786576 (318.50 GB)
telemt_user_unique_ips_current{user="hello"} 1220
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 29696.1 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798272
telemt_connections_bad_total 132638
telemt_connections_current 3003
telemt_connections_me_current 3003
telemt_handshake_timeouts_total 26224
telemt_upstream_connect_attempt_total 5355
telemt_upstream_connect_success_total 5355
telemt_upstream_connect_attempts_per_request{bucket="1"} 5355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3895
telemt_me_reconnect_success_total 3877
telemt_me_reader_eof_total 4106
telemt_me_idle_close_by_peer_total 4106
telemt_me_route_drop_no_conn_total 245719
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580297
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2997
telemt_desync_full_logged_total 980
telemt_desync_suppressed_total 2017
telemt_desync_frames_bucket_total{bucket="1_2"} 533
telemt_desync_frames_bucket_total{bucket="3_10"} 1067
telemt_desync_frames_bucket_total{bucket="gt_10"} 1397
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3951
telemt_me_writer_restored_same_endpoint_total 3861
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 580070
telemt_user_connections_current{user="hello"} 3003
telemt_user_octets_from_client{user="hello"} 11084481824 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 342093141488 (318.60 GB)
telemt_user_unique_ips_current{user="hello"} 994
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 29748.2 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 877668
telemt_connections_bad_total 87740
telemt_connections_current 2640
telemt_connections_me_current 2640
telemt_handshake_timeouts_total 21260
telemt_upstream_connect_attempt_total 5238
telemt_upstream_connect_success_total 5238
telemt_upstream_connect_attempts_per_request{bucket="1"} 5238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 3778
telemt_me_reconnect_success_total 3756
telemt_me_reader_eof_total 3959
telemt_me_idle_close_by_peer_total 3958
telemt_me_route_drop_no_conn_total 261377
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573969
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2104
telemt_desync_full_logged_total 770
telemt_desync_suppressed_total 1334
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 850
telemt_desync_frames_bucket_total{bucket="gt_10"} 876
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3810
telemt_me_writer_restored_same_endpoint_total 3732
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 572891
telemt_user_connections_current{user="hello"} 2640
telemt_user_octets_from_client{user="hello"} 8545295720 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 220417049708 (205.28 GB)
telemt_user_unique_ips_current{user="hello"} 896
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 29691.7 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1043374
telemt_connections_bad_total 291571
telemt_connections_current 2918
telemt_connections_me_current 2918
telemt_handshake_timeouts_total 27007
telemt_upstream_connect_attempt_total 5253
telemt_upstream_connect_success_total 5222
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 3770
telemt_me_reconnect_success_total 3746
telemt_me_reader_eof_total 3965
telemt_me_idle_close_by_peer_total 3965
telemt_me_route_drop_no_conn_total 253267
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616533
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3048
telemt_desync_full_logged_total 1024
telemt_desync_suppressed_total 2024
telemt_desync_frames_bucket_total{bucket="1_2"} 730
telemt_desync_frames_bucket_total{bucket="3_10"} 1309
telemt_desync_frames_bucket_total{bucket="gt_10"} 1009
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 3787
telemt_me_writer_restored_same_endpoint_total 3722
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 616449
telemt_user_connections_current{user="hello"} 2918
telemt_user_octets_from_client{user="hello"} 15964348296 (14.87 GB)
telemt_user_octets_to_client{user="hello"} 332737903536 (309.89 GB)
telemt_user_unique_ips_current{user="hello"} 1023
telemt_user_unique_ips_recent_window{user="hello"} 489
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 29703.3 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177562
telemt_connections_bad_total 11255
telemt_connections_current 633
telemt_connections_me_current 633
telemt_handshake_timeouts_total 1358
telemt_upstream_connect_attempt_total 8029
telemt_upstream_connect_success_total 7819
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 8029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4011
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_reconnect_attempts_total 10784
telemt_me_reconnect_success_total 6347
telemt_me_reader_eof_total 6723
telemt_me_idle_close_by_peer_total 6723
telemt_me_route_drop_no_conn_total 70903
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154833
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 190
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6508
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6317
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 154829
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 2600242520 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 86696510816 (80.74 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 29694.0 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 638764
telemt_connections_bad_total 82229
telemt_connections_current 2753
telemt_connections_me_current 2753
telemt_handshake_timeouts_total 27766
telemt_upstream_connect_attempt_total 5985
telemt_upstream_connect_success_total 5985
telemt_upstream_connect_attempts_per_request{bucket="1"} 5985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4531
telemt_me_reconnect_success_total 4518
telemt_me_reader_eof_total 4771
telemt_me_idle_close_by_peer_total 4771
telemt_me_route_drop_no_conn_total 225669
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508616
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2861
telemt_desync_full_logged_total 1025
telemt_desync_suppressed_total 1836
telemt_desync_frames_bucket_total{bucket="1_2"} 577
telemt_desync_frames_bucket_total{bucket="3_10"} 1094
telemt_desync_frames_bucket_total{bucket="gt_10"} 1190
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4569
telemt_me_writer_restored_same_endpoint_total 4503
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 508429
telemt_user_connections_current{user="hello"} 2753
telemt_user_octets_from_client{user="hello"} 6607025100 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 292802322772 (272.69 GB)
telemt_user_unique_ips_current{user="hello"} 886
telemt_user_unique_ips_recent_window{user="hello"} 364
```