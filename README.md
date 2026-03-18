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

# Server Metrics 2026-03-18 18:53:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12469.6 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335541
telemt_connections_bad_total 20771
telemt_handshake_timeouts_total 7539
telemt_upstream_connect_attempt_total 2049
telemt_upstream_connect_success_total 2049
telemt_upstream_connect_attempts_per_request{bucket="1"} 2049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1418
telemt_me_reconnect_success_total 1412
telemt_me_reader_eof_total 1465
telemt_me_idle_close_by_peer_total 1465
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 147652
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288139
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1703
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 1215
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 759
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1438
telemt_me_writer_restored_same_endpoint_total 1397
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 288021
telemt_user_connections_current{user="hello"} 1153
telemt_user_octets_from_client{user="hello"} 5415976428 (5.04 GB)
telemt_user_octets_to_client{user="hello"} 96476957408 (89.85 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 17297.7 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1677898
telemt_connections_bad_total 110235
telemt_connections_current 4148
telemt_connections_me_current 4148
telemt_handshake_timeouts_total 30799
telemt_upstream_connect_attempt_total 2841
telemt_upstream_connect_success_total 2827
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1935
telemt_me_reconnect_success_total 1919
telemt_me_reader_eof_total 1914
telemt_me_idle_close_by_peer_total 1913
telemt_me_route_drop_no_conn_total 1589847
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1454090
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4724
telemt_desync_full_logged_total 1511
telemt_desync_suppressed_total 3213
telemt_desync_frames_bucket_total{bucket="1_2"} 822
telemt_desync_frames_bucket_total{bucket="3_10"} 1860
telemt_desync_frames_bucket_total{bucket="gt_10"} 2042
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1866
telemt_me_writer_restored_same_endpoint_total 1917
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1449264
telemt_user_connections_current{user="hello"} 4148
telemt_user_octets_from_client{user="hello"} 19139162808 (17.82 GB)
telemt_user_octets_to_client{user="hello"} 454791874912 (423.56 GB)
telemt_user_unique_ips_current{user="hello"} 1279
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 17225.8 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1281800
telemt_connections_bad_total 112624
telemt_connections_current 3666
telemt_connections_me_current 3666
telemt_handshake_timeouts_total 26196
telemt_upstream_connect_attempt_total 2413
telemt_upstream_connect_success_total 2400
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1507
telemt_me_reconnect_success_total 1492
telemt_me_reader_eof_total 1584
telemt_me_idle_close_by_peer_total 1584
telemt_me_route_drop_no_conn_total 527473
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1017466
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4827
telemt_desync_full_logged_total 1487
telemt_desync_suppressed_total 3340
telemt_desync_frames_bucket_total{bucket="1_2"} 1185
telemt_desync_frames_bucket_total{bucket="3_10"} 1821
telemt_desync_frames_bucket_total{bucket="gt_10"} 1821
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 1535
telemt_me_writer_restored_same_endpoint_total 1475
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 1016765
telemt_user_connections_current{user="hello"} 3666
telemt_user_octets_from_client{user="hello"} 22648087080 (21.09 GB)
telemt_user_octets_to_client{user="hello"} 464849239016 (432.92 GB)
telemt_user_unique_ips_current{user="hello"} 1108
telemt_user_unique_ips_recent_window{user="hello"} 405
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 17940.2 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1905706
telemt_connections_bad_total 42528
telemt_connections_current 3052
telemt_connections_me_current 3052
telemt_handshake_timeouts_total 19558
telemt_upstream_connect_attempt_total 2666
telemt_upstream_connect_success_total 2647
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1750
telemt_me_reconnect_success_total 1728
telemt_me_reader_eof_total 1782
telemt_me_idle_close_by_peer_total 1781
telemt_me_route_drop_no_conn_total 3376829
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1710118
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6280
telemt_desync_full_logged_total 1535
telemt_desync_suppressed_total 4745
telemt_desync_frames_bucket_total{bucket="1_2"} 1398
telemt_desync_frames_bucket_total{bucket="3_10"} 2980
telemt_desync_frames_bucket_total{bucket="gt_10"} 1902
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 1735
telemt_me_writer_restored_same_endpoint_total 1717
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1710047
telemt_user_connections_current{user="hello"} 3052
telemt_user_octets_from_client{user="hello"} 15356949912 (14.30 GB)
telemt_user_octets_to_client{user="hello"} 263773187008 (245.66 GB)
telemt_user_unique_ips_current{user="hello"} 931
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12455.2 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 919850
telemt_connections_bad_total 157275
telemt_handshake_timeouts_total 8641
telemt_upstream_connect_attempt_total 2129
telemt_upstream_connect_success_total 2063
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 2129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 3515
telemt_me_reconnect_success_total 1421
telemt_me_reader_eof_total 1519
telemt_me_idle_close_by_peer_total 1519
telemt_me_route_drop_no_conn_total 390719
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682224
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2422
telemt_desync_full_logged_total 836
telemt_desync_suppressed_total 1586
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 1128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1508
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1395
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 681698
telemt_user_connections_current{user="hello"} 3475
telemt_user_octets_from_client{user="hello"} 11912990340 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 302556989392 (281.78 GB)
telemt_user_unique_ips_current{user="hello"} 1129
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 17389.4 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299287
telemt_connections_bad_total 10457
telemt_connections_current 735
telemt_connections_me_current 735
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3124
telemt_upstream_connect_attempt_total 7091
telemt_upstream_connect_success_total 7069
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 7091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 331803
telemt_me_reconnect_success_total 2335
telemt_me_reader_eof_total 2356
telemt_me_idle_close_by_peer_total 2356
telemt_me_route_drop_no_conn_total 189182
telemt_me_route_drop_channel_closed_total 91
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266433
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 531
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 15
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2286
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2324
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 270124
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 3762928085 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 56714686085 (52.82 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 16459.5 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 989726
telemt_connections_bad_total 69158
telemt_connections_current 3348
telemt_connections_me_current 3348
telemt_handshake_timeouts_total 18665
telemt_upstream_connect_attempt_total 2809
telemt_upstream_connect_success_total 2808
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17457
telemt_me_reconnect_success_total 1940
telemt_me_reader_eof_total 1955
telemt_me_idle_close_by_peer_total 1955
telemt_me_route_drop_no_conn_total 481154
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 829835
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3426
telemt_desync_full_logged_total 1166
telemt_desync_suppressed_total 2260
telemt_desync_frames_bucket_total{bucket="1_2"} 789
telemt_desync_frames_bucket_total{bucket="3_10"} 1206
telemt_desync_frames_bucket_total{bucket="gt_10"} 1431
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1910
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1879
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 828794
telemt_user_connections_current{user="hello"} 3348
telemt_user_octets_from_client{user="hello"} 16529205688 (15.39 GB)
telemt_user_octets_to_client{user="hello"} 450234115428 (419.31 GB)
telemt_user_unique_ips_current{user="hello"} 983
telemt_user_unique_ips_recent_window{user="hello"} 387
```