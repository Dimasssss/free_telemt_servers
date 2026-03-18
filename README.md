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

# Server Metrics 2026-03-18 18:42:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11854.0 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322085
telemt_connections_bad_total 19471
telemt_handshake_timeouts_total 7354
telemt_upstream_connect_attempt_total 1982
telemt_upstream_connect_success_total 1982
telemt_upstream_connect_attempts_per_request{bucket="1"} 1982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1351
telemt_me_reconnect_success_total 1345
telemt_me_reader_eof_total 1397
telemt_me_idle_close_by_peer_total 1397
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 142642
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276774
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1622
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 1159
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 505
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1371
telemt_me_writer_restored_same_endpoint_total 1330
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 276658
telemt_user_connections_current{user="hello"} 1237
telemt_user_octets_from_client{user="hello"} 5123316124 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 92929421904 (86.55 GB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 16683.2 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1631330
telemt_connections_bad_total 107854
telemt_connections_current 4056
telemt_connections_me_current 4056
telemt_handshake_timeouts_total 30389
telemt_upstream_connect_attempt_total 2756
telemt_upstream_connect_success_total 2742
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1893
telemt_me_reconnect_success_total 1877
telemt_me_reader_eof_total 1868
telemt_me_idle_close_by_peer_total 1867
telemt_me_route_drop_no_conn_total 1568359
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1412726
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4549
telemt_desync_full_logged_total 1448
telemt_desync_suppressed_total 3101
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1789
telemt_desync_frames_bucket_total{bucket="gt_10"} 1970
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1824
telemt_me_writer_restored_same_endpoint_total 1875
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1407893
telemt_user_connections_current{user="hello"} 4056
telemt_user_octets_from_client{user="hello"} 18624541404 (17.35 GB)
telemt_user_octets_to_client{user="hello"} 438148464688 (408.06 GB)
telemt_user_unique_ips_current{user="hello"} 1214
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 16611.4 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1228251
telemt_connections_bad_total 109540
telemt_connections_current 3765
telemt_connections_me_current 3765
telemt_handshake_timeouts_total 25124
telemt_upstream_connect_attempt_total 2331
telemt_upstream_connect_success_total 2318
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1468
telemt_me_reconnect_success_total 1454
telemt_me_reader_eof_total 1544
telemt_me_idle_close_by_peer_total 1544
telemt_me_route_drop_no_conn_total 511403
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 979509
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4610
telemt_desync_full_logged_total 1433
telemt_desync_suppressed_total 3177
telemt_desync_frames_bucket_total{bucket="1_2"} 1138
telemt_desync_frames_bucket_total{bucket="3_10"} 1748
telemt_desync_frames_bucket_total{bucket="gt_10"} 1724
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 1495
telemt_me_writer_restored_same_endpoint_total 1437
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 978807
telemt_user_connections_current{user="hello"} 3765
telemt_user_octets_from_client{user="hello"} 22118707408 (20.60 GB)
telemt_user_octets_to_client{user="hello"} 443751596492 (413.28 GB)
telemt_user_unique_ips_current{user="hello"} 1106
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 17325.7 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1824011
telemt_connections_bad_total 39309
telemt_connections_current 3020
telemt_connections_me_current 3020
telemt_handshake_timeouts_total 19194
telemt_upstream_connect_attempt_total 2616
telemt_upstream_connect_success_total 2597
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1700
telemt_me_reconnect_success_total 1678
telemt_me_reader_eof_total 1732
telemt_me_idle_close_by_peer_total 1731
telemt_me_route_drop_no_conn_total 3212517
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1637089
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6143
telemt_desync_full_logged_total 1500
telemt_desync_suppressed_total 4643
telemt_desync_frames_bucket_total{bucket="1_2"} 1356
telemt_desync_frames_bucket_total{bucket="3_10"} 2918
telemt_desync_frames_bucket_total{bucket="gt_10"} 1869
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 1685
telemt_me_writer_restored_same_endpoint_total 1667
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1637020
telemt_user_connections_current{user="hello"} 3020
telemt_user_octets_from_client{user="hello"} 14829096824 (13.81 GB)
telemt_user_octets_to_client{user="hello"} 255338811600 (237.80 GB)
telemt_user_unique_ips_current{user="hello"} 940
telemt_user_unique_ips_recent_window{user="hello"} 513
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11840.7 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 883780
telemt_connections_bad_total 154563
telemt_handshake_timeouts_total 8333
telemt_upstream_connect_attempt_total 2072
telemt_upstream_connect_success_total 2006
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 2072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 3458
telemt_me_reconnect_success_total 1365
telemt_me_reader_eof_total 1461
telemt_me_idle_close_by_peer_total 1461
telemt_me_route_drop_no_conn_total 375584
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651903
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2318
telemt_desync_full_logged_total 807
telemt_desync_suppressed_total 1511
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 789
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1452
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1339
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 651396
telemt_user_connections_current{user="hello"} 3450
telemt_user_octets_from_client{user="hello"} 11305446568 (10.53 GB)
telemt_user_octets_to_client{user="hello"} 285569999548 (265.96 GB)
telemt_user_unique_ips_current{user="hello"} 1109
telemt_user_unique_ips_recent_window{user="hello"} 420
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 16775.3 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291976
telemt_connections_bad_total 10452
telemt_connections_current 750
telemt_connections_me_current 750
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3017
telemt_upstream_connect_attempt_total 6967
telemt_upstream_connect_success_total 6947
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 6967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 331724
telemt_me_reconnect_success_total 2257
telemt_me_reader_eof_total 2270
telemt_me_idle_close_by_peer_total 2270
telemt_me_route_drop_no_conn_total 186566
telemt_me_route_drop_channel_closed_total 89
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259538
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 513
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 14
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2206
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2246
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 263229
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 3681569977 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 55226540273 (51.43 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 15845.0 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937986
telemt_connections_bad_total 58498
telemt_connections_current 3388
telemt_connections_me_current 3388
telemt_handshake_timeouts_total 17213
telemt_upstream_connect_attempt_total 2695
telemt_upstream_connect_success_total 2694
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17386
telemt_me_reconnect_success_total 1870
telemt_me_reader_eof_total 1878
telemt_me_idle_close_by_peer_total 1878
telemt_me_route_drop_no_conn_total 470298
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 796706
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3303
telemt_desync_full_logged_total 1122
telemt_desync_suppressed_total 2181
telemt_desync_frames_bucket_total{bucket="1_2"} 771
telemt_desync_frames_bucket_total{bucket="3_10"} 1175
telemt_desync_frames_bucket_total{bucket="gt_10"} 1357
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1839
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1809
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 795652
telemt_user_connections_current{user="hello"} 3388
telemt_user_octets_from_client{user="hello"} 16035726956 (14.93 GB)
telemt_user_octets_to_client{user="hello"} 428020729604 (398.63 GB)
telemt_user_unique_ips_current{user="hello"} 949
telemt_user_unique_ips_recent_window{user="hello"} 394
```