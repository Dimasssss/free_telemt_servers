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

# Server Metrics 2026-03-19 05:42:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 28468.6 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420701
telemt_connections_bad_total 41133
telemt_connections_current 1103
telemt_connections_me_current 1103
telemt_handshake_timeouts_total 21384
telemt_upstream_connect_attempt_total 5472
telemt_upstream_connect_success_total 5379
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 5472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3978
telemt_me_reconnect_success_total 3958
telemt_me_reader_eof_total 4175
telemt_me_idle_close_by_peer_total 4174
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 110924
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311285
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2055
telemt_desync_full_logged_total 574
telemt_desync_suppressed_total 1481
telemt_desync_frames_bucket_total{bucket="1_2"} 737
telemt_desync_frames_bucket_total{bucket="3_10"} 806
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3995
telemt_me_writer_restored_same_endpoint_total 3941
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 308537
telemt_user_connections_current{user="hello"} 1103
telemt_user_octets_from_client{user="hello"} 3898996088 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 104885927712 (97.68 GB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 28472.7 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854809
telemt_connections_bad_total 49879
telemt_connections_current 2914
telemt_connections_me_current 2914
telemt_handshake_timeouts_total 24434
telemt_upstream_connect_attempt_total 5312
telemt_upstream_connect_success_total 5211
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 5312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 3798
telemt_me_reconnect_success_total 3778
telemt_me_reader_eof_total 3985
telemt_me_idle_close_by_peer_total 3985
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 264687
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707217
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2874
telemt_desync_full_logged_total 979
telemt_desync_suppressed_total 1895
telemt_desync_frames_bucket_total{bucket="1_2"} 541
telemt_desync_frames_bucket_total{bucket="3_10"} 1076
telemt_desync_frames_bucket_total{bucket="gt_10"} 1257
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3844
telemt_me_writer_restored_same_endpoint_total 3759
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 707094
telemt_user_connections_current{user="hello"} 2914
telemt_user_octets_from_client{user="hello"} 16695131748 (15.55 GB)
telemt_user_octets_to_client{user="hello"} 309738633456 (288.47 GB)
telemt_user_unique_ips_current{user="hello"} 1086
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 28470.7 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726327
telemt_connections_bad_total 123939
telemt_connections_current 2306
telemt_connections_me_current 2306
telemt_handshake_timeouts_total 24842
telemt_upstream_connect_attempt_total 5146
telemt_upstream_connect_success_total 5146
telemt_upstream_connect_attempts_per_request{bucket="1"} 5146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3730
telemt_me_reconnect_success_total 3715
telemt_me_reader_eof_total 3939
telemt_me_idle_close_by_peer_total 3939
telemt_me_route_drop_no_conn_total 219342
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 525689
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2759
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 1863
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 974
telemt_desync_frames_bucket_total{bucket="gt_10"} 1323
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3783
telemt_me_writer_restored_same_endpoint_total 3699
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 525675
telemt_user_connections_current{user="hello"} 2306
telemt_user_octets_from_client{user="hello"} 10417096996 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 316488007764 (294.75 GB)
telemt_user_unique_ips_current{user="hello"} 880
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 28523.2 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806437
telemt_connections_bad_total 87355
telemt_connections_current 2244
telemt_connections_me_current 2244
telemt_handshake_timeouts_total 19773
telemt_upstream_connect_attempt_total 5021
telemt_upstream_connect_success_total 5021
telemt_upstream_connect_attempts_per_request{bucket="1"} 5021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 3610
telemt_me_reconnect_success_total 3589
telemt_me_reader_eof_total 3789
telemt_me_idle_close_by_peer_total 3788
telemt_me_route_drop_no_conn_total 235842
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520967
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1704
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 1079
telemt_desync_frames_bucket_total{bucket="1_2"} 316
telemt_desync_frames_bucket_total{bucket="3_10"} 694
telemt_desync_frames_bucket_total{bucket="gt_10"} 694
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3639
telemt_me_writer_restored_same_endpoint_total 3565
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 519884
telemt_user_connections_current{user="hello"} 2244
telemt_user_octets_from_client{user="hello"} 7785531712 (7.25 GB)
telemt_user_octets_to_client{user="hello"} 199727538956 (186.01 GB)
telemt_user_unique_ips_current{user="hello"} 802
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 28466.4 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 956881
telemt_connections_bad_total 275599
telemt_connections_current 2366
telemt_connections_me_current 2366
telemt_handshake_timeouts_total 25942
telemt_upstream_connect_attempt_total 5106
telemt_upstream_connect_success_total 5075
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 3666
telemt_me_reconnect_success_total 3645
telemt_me_reader_eof_total 3859
telemt_me_idle_close_by_peer_total 3859
telemt_me_route_drop_no_conn_total 229377
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558212
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2749
telemt_desync_full_logged_total 948
telemt_desync_suppressed_total 1801
telemt_desync_frames_bucket_total{bucket="1_2"} 665
telemt_desync_frames_bucket_total{bucket="3_10"} 1188
telemt_desync_frames_bucket_total{bucket="gt_10"} 896
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3684
telemt_me_writer_restored_same_endpoint_total 3621
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 558123
telemt_user_connections_current{user="hello"} 2366
telemt_user_octets_from_client{user="hello"} 15185048224 (14.14 GB)
telemt_user_octets_to_client{user="hello"} 311630072600 (290.23 GB)
telemt_user_unique_ips_current{user="hello"} 895
telemt_user_unique_ips_recent_window{user="hello"} 343
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 28478.2 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163020
telemt_connections_bad_total 10788
telemt_connections_current 639
telemt_connections_me_current 639
telemt_handshake_timeouts_total 1279
telemt_upstream_connect_attempt_total 7839
telemt_upstream_connect_success_total 7632
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 7839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3928
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 10640
telemt_me_reconnect_success_total 6203
telemt_me_reader_eof_total 6569
telemt_me_idle_close_by_peer_total 6569
telemt_me_route_drop_no_conn_total 65574
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142405
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 188
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6364
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6173
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 142400
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 2405570904 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 81961710084 (76.33 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 28468.9 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565312
telemt_connections_bad_total 62089
telemt_connections_current 2264
telemt_connections_me_current 2264
telemt_handshake_timeouts_total 26097
telemt_upstream_connect_attempt_total 5821
telemt_upstream_connect_success_total 5821
telemt_upstream_connect_attempts_per_request{bucket="1"} 5821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4411
telemt_me_reconnect_success_total 4398
telemt_me_reader_eof_total 4643
telemt_me_idle_close_by_peer_total 4643
telemt_me_route_drop_no_conn_total 189845
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459485
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2619
telemt_desync_full_logged_total 941
telemt_desync_suppressed_total 1678
telemt_desync_frames_bucket_total{bucket="1_2"} 541
telemt_desync_frames_bucket_total{bucket="3_10"} 1004
telemt_desync_frames_bucket_total{bucket="gt_10"} 1074
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4447
telemt_me_writer_restored_same_endpoint_total 4383
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 459359
telemt_user_connections_current{user="hello"} 2264
telemt_user_octets_from_client{user="hello"} 5836805712 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 270191379352 (251.64 GB)
telemt_user_unique_ips_current{user="hello"} 786
telemt_user_unique_ips_recent_window{user="hello"} 281
```