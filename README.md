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

# Server Metrics 2026-03-18 17:00:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 5698.3 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176915
telemt_connections_bad_total 12919
telemt_handshake_timeouts_total 5443
telemt_upstream_connect_attempt_total 886
telemt_upstream_connect_success_total 886
telemt_upstream_connect_attempts_per_request{bucket="1"} 886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 558
telemt_me_reconnect_success_total 556
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 90331
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146279
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 823
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 573
telemt_me_writer_restored_same_endpoint_total 543
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 146216
telemt_user_connections_current{user="hello"} 1445
telemt_user_octets_from_client{user="hello"} 2003830760 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 50355264552 (46.90 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 10526.8 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1066048
telemt_connections_bad_total 68624
telemt_connections_current 3848
telemt_connections_me_current 3848
telemt_handshake_timeouts_total 16307
telemt_upstream_connect_attempt_total 1901
telemt_upstream_connect_success_total 1891
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1343
telemt_me_reconnect_success_total 1333
telemt_me_reader_eof_total 1284
telemt_me_idle_close_by_peer_total 1283
telemt_me_route_drop_no_conn_total 1022526
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 928791
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2645
telemt_desync_full_logged_total 845
telemt_desync_suppressed_total 1800
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 1059
telemt_desync_frames_bucket_total{bucket="gt_10"} 1059
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1265
telemt_me_writer_restored_same_endpoint_total 1331
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 927946
telemt_user_connections_current{user="hello"} 3848
telemt_user_octets_from_client{user="hello"} 11822768604 (11.01 GB)
telemt_user_octets_to_client{user="hello"} 272299168656 (253.60 GB)
telemt_user_unique_ips_current{user="hello"} 1192
telemt_user_unique_ips_recent_window{user="hello"} 600
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 10454.8 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 729938
telemt_connections_bad_total 51317
telemt_connections_current 3417
telemt_connections_me_current 3417
telemt_handshake_timeouts_total 15712
telemt_upstream_connect_attempt_total 1470
telemt_upstream_connect_success_total 1463
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 904
telemt_me_reader_eof_total 952
telemt_me_idle_close_by_peer_total 952
telemt_me_route_drop_no_conn_total 359611
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616722
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2494
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1765
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 928
telemt_desync_frames_bucket_total{bucket="gt_10"} 999
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 936
telemt_me_writer_restored_same_endpoint_total 887
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 616375
telemt_user_connections_current{user="hello"} 3417
telemt_user_octets_from_client{user="hello"} 11331711028 (10.55 GB)
telemt_user_octets_to_client{user="hello"} 255969260872 (238.39 GB)
telemt_user_unique_ips_current{user="hello"} 1025
telemt_user_unique_ips_recent_window{user="hello"} 512
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 11169.4 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1066416
telemt_connections_bad_total 24654
telemt_connections_current 2918
telemt_connections_me_current 2918
telemt_handshake_timeouts_total 13663
telemt_upstream_connect_attempt_total 1791
telemt_upstream_connect_success_total 1779
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1182
telemt_me_reconnect_success_total 1172
telemt_me_reader_eof_total 1188
telemt_me_idle_close_by_peer_total 1187
telemt_me_route_drop_no_conn_total 1762944
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956391
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3537
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 2644
telemt_desync_frames_bucket_total{bucket="1_2"} 826
telemt_desync_frames_bucket_total{bucket="3_10"} 1625
telemt_desync_frames_bucket_total{bucket="gt_10"} 1086
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1164
telemt_me_writer_restored_same_endpoint_total 1161
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 956326
telemt_user_connections_current{user="hello"} 2918
telemt_user_octets_from_client{user="hello"} 8357877232 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 168883327352 (157.28 GB)
telemt_user_unique_ips_current{user="hello"} 883
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5684.2 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445792
telemt_connections_bad_total 87917
telemt_handshake_timeouts_total 4127
telemt_upstream_connect_attempt_total 1030
telemt_upstream_connect_success_total 999
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 1030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1665
telemt_me_reconnect_success_total 665
telemt_me_reader_eof_total 691
telemt_me_idle_close_by_peer_total 691
telemt_me_route_drop_no_conn_total 187729
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320284
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1151
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 700
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 639
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 319876
telemt_user_connections_current{user="hello"} 3194
telemt_user_octets_from_client{user="hello"} 4806780112 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 128905955264 (120.05 GB)
telemt_user_unique_ips_current{user="hello"} 1025
telemt_user_unique_ips_recent_window{user="hello"} 486
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 10623.6 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194412
telemt_connections_bad_total 7671
telemt_connections_current 896
telemt_connections_me_current 896
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1891
telemt_upstream_connect_attempt_total 6010
telemt_upstream_connect_success_total 5999
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 6010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2678
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 331077
telemt_me_reconnect_success_total 1614
telemt_me_reader_eof_total 1577
telemt_me_idle_close_by_peer_total 1577
telemt_me_route_drop_no_conn_total 107313
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171516
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1550
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1603
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 175241
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 2615986493 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 37476719633 (34.90 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 9688.7 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 579938
telemt_connections_bad_total 24012
telemt_connections_current 2778
telemt_connections_me_current 2778
telemt_handshake_timeouts_total 11623
telemt_upstream_connect_attempt_total 1768
telemt_upstream_connect_success_total 1767
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16762
telemt_me_reconnect_success_total 1251
telemt_me_reader_eof_total 1218
telemt_me_idle_close_by_peer_total 1218
telemt_me_route_drop_no_conn_total 365655
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500133
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1767
telemt_desync_full_logged_total 622
telemt_desync_suppressed_total 1145
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 719
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1210
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1190
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 499223
telemt_user_connections_current{user="hello"} 2778
telemt_user_octets_from_client{user="hello"} 8834967008 (8.23 GB)
telemt_user_octets_to_client{user="hello"} 232390594160 (216.43 GB)
telemt_user_unique_ips_current{user="hello"} 854
telemt_user_unique_ips_recent_window{user="hello"} 401
```