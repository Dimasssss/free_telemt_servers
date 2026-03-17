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

# Server Metrics 2026-03-17 17:32:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 82061.6 (22h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 986959
telemt_connections_bad_total 6536
telemt_handshake_timeouts_total 27771
telemt_upstream_connect_attempt_total 19453
telemt_upstream_connect_success_total 18974
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 19453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 172
telemt_me_reconnect_attempts_total 29657
telemt_me_reconnect_success_total 12541
telemt_me_reader_eof_total 13663
telemt_me_idle_close_by_peer_total 13662
telemt_me_route_drop_no_conn_total 451009
telemt_me_route_drop_channel_closed_total 123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 902781
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5998
telemt_desync_full_logged_total 1703
telemt_desync_suppressed_total 4295
telemt_desync_frames_bucket_total{bucket="1_2"} 1661
telemt_desync_frames_bucket_total{bucket="3_10"} 2311
telemt_desync_frames_bucket_total{bucket="gt_10"} 2026
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13252
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12519
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 897039
telemt_user_connections_current{user="hello"} 1113
telemt_user_octets_from_client{user="hello"} 13771390907 (12.83 GB)
telemt_user_octets_to_client{user="hello"} 306681043375 (285.62 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 82313.7 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 838253
telemt_connections_bad_total 49833
telemt_handshake_timeouts_total 31304
telemt_upstream_connect_attempt_total 325320
telemt_upstream_connect_success_total 324563
telemt_upstream_connect_fail_total 753
telemt_upstream_connect_attempts_per_request{bucket="1"} 325316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 269102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31003
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 753
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 51210
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15294
telemt_me_idle_close_by_peer_total 15294
telemt_me_route_drop_no_conn_total 234915
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413159
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1549
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 1058
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14904
telemt_me_refill_failed_total 1172
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1339
telemt_user_connections_total{user="hello"} 719916
telemt_user_connections_current{user="hello"} 2048
telemt_user_octets_from_client{user="hello"} 9594422547 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 194472525736 (181.12 GB)
telemt_user_msgs_from_client{user="hello"} 5112939
telemt_user_msgs_to_client{user="hello"} 21362595
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 82089.2 (22h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430366
telemt_connections_bad_total 13897
telemt_handshake_timeouts_total 20595
telemt_upstream_connect_attempt_total 20606
telemt_upstream_connect_success_total 20488
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 36968
telemt_me_reconnect_success_total 16300
telemt_me_reader_eof_total 17835
telemt_me_idle_close_by_peer_total 17828
telemt_me_route_drop_no_conn_total 206694
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374700
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1068
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 745
telemt_desync_frames_bucket_total{bucket="1_2"} 359
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 17164
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16288
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 864
telemt_user_connections_total{user="hello"} 372855
telemt_user_connections_current{user="hello"} 1387
telemt_user_octets_from_client{user="hello"} 24580562344 (22.89 GB)
telemt_user_octets_to_client{user="hello"} 131399801272 (122.38 GB)
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 82148.7 (22h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 897863
telemt_connections_bad_total 20294
telemt_handshake_timeouts_total 17481
telemt_upstream_connect_attempt_total 80370
telemt_upstream_connect_success_total 79975
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 80370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10875
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 32759
telemt_me_reconnect_success_total 12460
telemt_me_reader_eof_total 13767
telemt_me_idle_close_by_peer_total 13766
telemt_me_route_drop_no_conn_total 381430
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 717084
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2324
telemt_desync_full_logged_total 745
telemt_desync_suppressed_total 1579
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 1044
telemt_desync_frames_bucket_total{bucket="gt_10"} 732
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13320
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12451
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 860
telemt_user_connections_total{user="hello"} 780201
telemt_user_connections_current{user="hello"} 1873
telemt_user_octets_from_client{user="hello"} 9461669787 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 253678788625 (236.26 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 82120.3 (22h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470254
telemt_connections_bad_total 71618
telemt_handshake_timeouts_total 4444
telemt_upstream_connect_attempt_total 38769
telemt_upstream_connect_success_total 38268
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 38769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50113
telemt_me_reconnect_success_total 17635
telemt_me_reader_eof_total 19258
telemt_me_idle_close_by_peer_total 19256
telemt_me_route_drop_no_conn_total 138194
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356360
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1566
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 1182
telemt_desync_frames_bucket_total{bucket="1_2"} 648
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18943
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17627
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1308
telemt_user_connections_total{user="hello"} 373064
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 6149696188 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 165874985544 (154.48 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 82282.2 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 833355
telemt_connections_bad_total 60427
telemt_handshake_timeouts_total 7930
telemt_upstream_connect_attempt_total 16561
telemt_upstream_connect_success_total 16469
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 23595
telemt_me_reconnect_success_total 12326
telemt_me_reader_eof_total 13417
telemt_me_idle_close_by_peer_total 13415
telemt_me_route_drop_no_conn_total 621724
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 858058
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1534
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 1005
telemt_desync_frames_bucket_total{bucket="1_2"} 369
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 570
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12888
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12312
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 562
telemt_user_connections_total{user="hello"} 721122
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 10873031720 (10.13 GB)
telemt_user_octets_to_client{user="hello"} 317082083188 (295.31 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 30048.7 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121062
telemt_connections_bad_total 8133
telemt_handshake_timeouts_total 4408
telemt_upstream_connect_attempt_total 14378
telemt_upstream_connect_success_total 14253
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 14378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24133
telemt_me_reconnect_success_total 12557
telemt_me_reader_eof_total 13300
telemt_me_idle_close_by_peer_total 13300
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 30783
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102008
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 155
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 13069
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12534
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 101980
telemt_user_connections_current{user="hello"} 1183
telemt_user_octets_from_client{user="hello"} 5131325797 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 104383424490 (97.21 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 143
```