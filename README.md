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

# Server Metrics 2026-03-18 03:29:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 117839.9 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1347500
telemt_connections_bad_total 10391
telemt_handshake_timeouts_total 33444
telemt_upstream_connect_attempt_total 26027
telemt_upstream_connect_success_total 25517
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 26027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34517
telemt_me_reconnect_success_total 17374
telemt_me_reader_eof_total 18851
telemt_me_idle_close_by_peer_total 18850
telemt_me_route_drop_no_conn_total 579457
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1240822
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7869
telemt_desync_full_logged_total 2339
telemt_desync_suppressed_total 5530
telemt_desync_frames_bucket_total{bucket="1_2"} 2083
telemt_desync_frames_bucket_total{bucket="3_10"} 3008
telemt_desync_frames_bucket_total{bucket="gt_10"} 2778
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 18170
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17352
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 796
telemt_user_connections_total{user="hello"} 1235031
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 24952512795 (23.24 GB)
telemt_user_octets_to_client{user="hello"} 438639334683 (408.51 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 118091.5 (32h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1428002
telemt_connections_bad_total 64623
telemt_handshake_timeouts_total 47739
telemt_upstream_connect_attempt_total 469238
telemt_upstream_connect_success_total 467640
telemt_upstream_connect_fail_total 1598
telemt_upstream_connect_attempts_per_request{bucket="1"} 469238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1598
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125544
telemt_me_reconnect_success_total 18821
telemt_me_reader_eof_total 21058
telemt_me_idle_close_by_peer_total 21045
telemt_me_route_drop_no_conn_total 368507
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 801478
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3714
telemt_desync_full_logged_total 1277
telemt_desync_suppressed_total 2437
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 1539
telemt_desync_frames_bucket_total{bucket="gt_10"} 1447
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 20434
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18803
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1613
telemt_user_connections_total{user="hello"} 1243810
telemt_user_connections_current{user="hello"} 900
telemt_user_octets_from_client{user="hello"} 16677925609 (15.53 GB)
telemt_user_octets_to_client{user="hello"} 441320860730 (411.01 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 117867.3 (32h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 873072
telemt_connections_bad_total 61501
telemt_handshake_timeouts_total 25114
telemt_upstream_connect_attempt_total 27358
telemt_upstream_connect_success_total 27200
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 27358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 41999
telemt_me_reconnect_success_total 21303
telemt_me_reader_eof_total 23166
telemt_me_idle_close_by_peer_total 23159
telemt_me_route_drop_no_conn_total 340860
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734308
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2305
telemt_desync_full_logged_total 750
telemt_desync_suppressed_total 1555
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 888
telemt_desync_frames_bucket_total{bucket="gt_10"} 755
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 22235
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21291
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 932
telemt_user_connections_total{user="hello"} 732423
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 44353064600 (41.31 GB)
telemt_user_octets_to_client{user="hello"} 328492589136 (305.93 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 117926.8 (32h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1349413
telemt_connections_bad_total 63272
telemt_handshake_timeouts_total 23730
telemt_upstream_connect_attempt_total 90215
telemt_upstream_connect_success_total 87789
telemt_upstream_connect_fail_total 2426
telemt_upstream_connect_attempts_per_request{bucket="1"} 90215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2426
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37573
telemt_me_reconnect_success_total 17168
telemt_me_reader_eof_total 18878
telemt_me_idle_close_by_peer_total 18875
telemt_me_route_drop_no_conn_total 550401
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1095376
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4073
telemt_desync_full_logged_total 1343
telemt_desync_suppressed_total 2730
telemt_desync_frames_bucket_total{bucket="1_2"} 1003
telemt_desync_frames_bucket_total{bucket="3_10"} 1698
telemt_desync_frames_bucket_total{bucket="gt_10"} 1372
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18127
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17148
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 959
telemt_user_connections_total{user="hello"} 1158741
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 18035777594 (16.80 GB)
telemt_user_octets_to_client{user="hello"} 553115258226 (515.13 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 117898.8 (32h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 908257
telemt_connections_bad_total 101536
telemt_handshake_timeouts_total 7238
telemt_upstream_connect_attempt_total 47079
telemt_upstream_connect_success_total 46437
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 47079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59065
telemt_me_reconnect_success_total 24101
telemt_me_reader_eof_total 26110
telemt_me_idle_close_by_peer_total 26107
telemt_me_route_drop_no_conn_total 290157
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 735388
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3325
telemt_desync_full_logged_total 1004
telemt_desync_suppressed_total 2321
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1326
telemt_desync_frames_bucket_total{bucket="gt_10"} 970
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25571
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24093
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1470
telemt_user_connections_total{user="hello"} 751905
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 14357852880 (13.37 GB)
telemt_user_octets_to_client{user="hello"} 370380412688 (344.94 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 118059.6 (32h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1149719
telemt_connections_bad_total 126839
telemt_handshake_timeouts_total 10154
telemt_upstream_connect_attempt_total 23519
telemt_upstream_connect_success_total 23383
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 23519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28784
telemt_me_reconnect_success_total 17492
telemt_me_reader_eof_total 18962
telemt_me_idle_close_by_peer_total 18960
telemt_me_route_drop_no_conn_total 793548
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125602
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 106
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18117
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17478
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 941233
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 15063694952 (14.03 GB)
telemt_user_octets_to_client{user="hello"} 412348994248 (384.03 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 65826.9 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454123
telemt_connections_bad_total 45132
telemt_handshake_timeouts_total 11873
telemt_upstream_connect_attempt_total 23953
telemt_upstream_connect_success_total 23711
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 23953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31870
telemt_me_reconnect_success_total 20260
telemt_me_reader_eof_total 21405
telemt_me_idle_close_by_peer_total 21405
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 111416
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328994
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1449
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 979
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20842
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20218
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 328787
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 22881399297 (21.31 GB)
telemt_user_octets_to_client{user="hello"} 273750173442 (254.95 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 51
```