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

# Server Metrics 2026-03-18 18:12:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10010.2 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280364
telemt_connections_bad_total 17566
telemt_handshake_timeouts_total 6921
telemt_upstream_connect_attempt_total 1671
telemt_upstream_connect_success_total 1671
telemt_upstream_connect_attempts_per_request{bucket="1"} 1671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 1127
telemt_me_reconnect_success_total 1123
telemt_me_reader_eof_total 1153
telemt_me_idle_close_by_peer_total 1153
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 127824
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239167
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1291
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 899
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 411
telemt_desync_frames_bucket_total{bucket="gt_10"} 576
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1146
telemt_me_writer_restored_same_endpoint_total 1108
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 239062
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 3379022548 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 81548788424 (75.95 GB)
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 14838.2 (4h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1483964
telemt_connections_bad_total 100172
telemt_connections_current 3826
telemt_connections_me_current 3826
telemt_handshake_timeouts_total 27803
telemt_upstream_connect_attempt_total 2524
telemt_upstream_connect_success_total 2511
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1748
telemt_me_reconnect_success_total 1733
telemt_me_reader_eof_total 1713
telemt_me_idle_close_by_peer_total 1712
telemt_me_route_drop_no_conn_total 1494674
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1283334
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4002
telemt_desync_full_logged_total 1262
telemt_desync_suppressed_total 2740
telemt_desync_frames_bucket_total{bucket="1_2"} 706
telemt_desync_frames_bucket_total{bucket="3_10"} 1578
telemt_desync_frames_bucket_total{bucket="gt_10"} 1718
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1676
telemt_me_writer_restored_same_endpoint_total 1731
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1278658
telemt_user_connections_current{user="hello"} 3826
telemt_user_octets_from_client{user="hello"} 16709926824 (15.56 GB)
telemt_user_octets_to_client{user="hello"} 383307044872 (356.98 GB)
telemt_user_unique_ips_current{user="hello"} 1186
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 14766.7 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055973
telemt_connections_bad_total 85527
telemt_connections_current 3434
telemt_connections_me_current 3434
telemt_handshake_timeouts_total 23070
telemt_upstream_connect_attempt_total 2094
telemt_upstream_connect_success_total 2083
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1319
telemt_me_reconnect_success_total 1305
telemt_me_reader_eof_total 1383
telemt_me_idle_close_by_peer_total 1383
telemt_me_route_drop_no_conn_total 462846
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 867842
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3901
telemt_desync_full_logged_total 1193
telemt_desync_suppressed_total 2708
telemt_desync_frames_bucket_total{bucket="1_2"} 978
telemt_desync_frames_bucket_total{bucket="3_10"} 1464
telemt_desync_frames_bucket_total{bucket="gt_10"} 1459
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1342
telemt_me_writer_restored_same_endpoint_total 1288
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 867471
telemt_user_connections_current{user="hello"} 3434
telemt_user_octets_from_client{user="hello"} 20360137956 (18.96 GB)
telemt_user_octets_to_client{user="hello"} 380698834028 (354.55 GB)
telemt_user_unique_ips_current{user="hello"} 1069
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 15480.8 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1565075
telemt_connections_bad_total 35420
telemt_connections_current 2872
telemt_connections_me_current 2872
telemt_handshake_timeouts_total 17034
telemt_upstream_connect_attempt_total 2380
telemt_upstream_connect_success_total 2362
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1551
telemt_me_reconnect_success_total 1531
telemt_me_reader_eof_total 1573
telemt_me_idle_close_by_peer_total 1572
telemt_me_route_drop_no_conn_total 2638445
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1401273
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5400
telemt_desync_full_logged_total 1331
telemt_desync_suppressed_total 4069
telemt_desync_frames_bucket_total{bucket="1_2"} 1201
telemt_desync_frames_bucket_total{bucket="3_10"} 2552
telemt_desync_frames_bucket_total{bucket="gt_10"} 1647
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1534
telemt_me_writer_restored_same_endpoint_total 1520
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 1401207
telemt_user_connections_current{user="hello"} 2872
telemt_user_octets_from_client{user="hello"} 13354678004 (12.44 GB)
telemt_user_octets_to_client{user="hello"} 229911225596 (214.12 GB)
telemt_user_unique_ips_current{user="hello"} 877
telemt_user_unique_ips_recent_window{user="hello"} 366
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9995.7 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 757820
telemt_connections_bad_total 139789
telemt_handshake_timeouts_total 7346
telemt_upstream_connect_attempt_total 1777
telemt_upstream_connect_success_total 1719
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 1776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 3267
telemt_me_reconnect_success_total 1177
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 318684
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552232
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1994
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1306
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 948
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1258
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1151
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 551750
telemt_user_connections_current{user="hello"} 3566
telemt_user_octets_from_client{user="hello"} 9041179504 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 234299395712 (218.21 GB)
telemt_user_unique_ips_current{user="hello"} 1114
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 14931.6 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269841
telemt_connections_bad_total 10060
telemt_connections_current 863
telemt_connections_me_current 863
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2854
telemt_upstream_connect_attempt_total 6662
telemt_upstream_connect_success_total 6646
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3087
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 331509
telemt_me_reconnect_success_total 2042
telemt_me_reader_eof_total 2039
telemt_me_idle_close_by_peer_total 2039
telemt_me_route_drop_no_conn_total 177065
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239257
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 456
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 12
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 1988
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2031
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 242952
telemt_user_connections_current{user="hello"} 863
telemt_user_octets_from_client{user="hello"} 3514033825 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 49717170657 (46.30 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 14000.2 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 836711
telemt_connections_bad_total 56400
telemt_connections_current 2910
telemt_connections_me_current 2910
telemt_handshake_timeouts_total 14956
telemt_upstream_connect_attempt_total 2423
telemt_upstream_connect_success_total 2422
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17200
telemt_me_reconnect_success_total 1685
telemt_me_reader_eof_total 1680
telemt_me_idle_close_by_peer_total 1680
telemt_me_route_drop_no_conn_total 437114
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706243
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2859
telemt_desync_full_logged_total 980
telemt_desync_suppressed_total 1879
telemt_desync_frames_bucket_total{bucket="1_2"} 682
telemt_desync_frames_bucket_total{bucket="3_10"} 1029
telemt_desync_frames_bucket_total{bucket="gt_10"} 1148
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1650
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1624
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 705252
telemt_user_connections_current{user="hello"} 2910
telemt_user_octets_from_client{user="hello"} 13700856824 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 361494282708 (336.67 GB)
telemt_user_unique_ips_current{user="hello"} 919
telemt_user_unique_ips_recent_window{user="hello"} 381
```