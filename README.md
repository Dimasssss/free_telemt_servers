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

# Server Metrics 2026-03-18 18:27:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10933.1 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301070
telemt_connections_bad_total 18396
telemt_handshake_timeouts_total 7256
telemt_upstream_connect_attempt_total 1811
telemt_upstream_connect_success_total 1811
telemt_upstream_connect_attempts_per_request{bucket="1"} 1811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1223
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1260
telemt_me_idle_close_by_peer_total 1260
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 134991
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257711
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1439
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 1017
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 449
telemt_desync_frames_bucket_total{bucket="gt_10"} 633
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1243
telemt_me_writer_restored_same_endpoint_total 1203
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 257603
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 3589548540 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 87571579688 (81.56 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 15761.2 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1556995
telemt_connections_bad_total 104307
telemt_connections_current 3822
telemt_connections_me_current 3822
telemt_handshake_timeouts_total 29592
telemt_upstream_connect_attempt_total 2637
telemt_upstream_connect_success_total 2624
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1818
telemt_me_reconnect_success_total 1803
telemt_me_reader_eof_total 1787
telemt_me_idle_close_by_peer_total 1786
telemt_me_route_drop_no_conn_total 1524416
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1346684
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4295
telemt_desync_full_logged_total 1358
telemt_desync_suppressed_total 2937
telemt_desync_frames_bucket_total{bucket="1_2"} 757
telemt_desync_frames_bucket_total{bucket="3_10"} 1688
telemt_desync_frames_bucket_total{bucket="gt_10"} 1850
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1746
telemt_me_writer_restored_same_endpoint_total 1801
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1342040
telemt_user_connections_current{user="hello"} 3822
telemt_user_octets_from_client{user="hello"} 17825266268 (16.60 GB)
telemt_user_octets_to_client{user="hello"} 410218677660 (382.05 GB)
telemt_user_unique_ips_current{user="hello"} 1188
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 15689.9 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138791
telemt_connections_bad_total 94874
telemt_connections_current 3487
telemt_connections_me_current 3487
telemt_handshake_timeouts_total 23948
telemt_upstream_connect_attempt_total 2204
telemt_upstream_connect_success_total 2193
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1386
telemt_me_reconnect_success_total 1372
telemt_me_reader_eof_total 1456
telemt_me_idle_close_by_peer_total 1456
telemt_me_route_drop_no_conn_total 487992
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 922926
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4263
telemt_desync_full_logged_total 1321
telemt_desync_suppressed_total 2942
telemt_desync_frames_bucket_total{bucket="1_2"} 1058
telemt_desync_frames_bucket_total{bucket="3_10"} 1602
telemt_desync_frames_bucket_total{bucket="gt_10"} 1603
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 1411
telemt_me_writer_restored_same_endpoint_total 1355
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 922212
telemt_user_connections_current{user="hello"} 3487
telemt_user_octets_from_client{user="hello"} 21378840380 (19.91 GB)
telemt_user_octets_to_client{user="hello"} 411790830824 (383.51 GB)
telemt_user_unique_ips_current{user="hello"} 1062
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 16403.8 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1665842
telemt_connections_bad_total 38046
telemt_connections_current 3173
telemt_connections_me_current 3173
telemt_handshake_timeouts_total 18512
telemt_upstream_connect_attempt_total 2493
telemt_upstream_connect_success_total 2474
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1620
telemt_me_reconnect_success_total 1598
telemt_me_reader_eof_total 1646
telemt_me_idle_close_by_peer_total 1645
telemt_me_route_drop_no_conn_total 2782221
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1490714
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5732
telemt_desync_full_logged_total 1425
telemt_desync_suppressed_total 4307
telemt_desync_frames_bucket_total{bucket="1_2"} 1300
telemt_desync_frames_bucket_total{bucket="3_10"} 2679
telemt_desync_frames_bucket_total{bucket="gt_10"} 1753
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1603
telemt_me_writer_restored_same_endpoint_total 1587
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1490660
telemt_user_connections_current{user="hello"} 3173
telemt_user_octets_from_client{user="hello"} 13975058604 (13.02 GB)
telemt_user_octets_to_client{user="hello"} 244031861028 (227.27 GB)
telemt_user_unique_ips_current{user="hello"} 932
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10918.7 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826691
telemt_connections_bad_total 151353
telemt_handshake_timeouts_total 7909
telemt_upstream_connect_attempt_total 1902
telemt_upstream_connect_success_total 1836
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 1902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 3337
telemt_me_reconnect_success_total 1245
telemt_me_reader_eof_total 1334
telemt_me_idle_close_by_peer_total 1334
telemt_me_route_drop_no_conn_total 350201
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 603351
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2129
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 721
telemt_desync_frames_bucket_total{bucket="gt_10"} 1012
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1330
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1219
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 602862
telemt_user_connections_current{user="hello"} 3579
telemt_user_octets_from_client{user="hello"} 10253712608 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 259712124144 (241.88 GB)
telemt_user_unique_ips_current{user="hello"} 1124
telemt_user_unique_ips_recent_window{user="hello"} 423
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 15852.9 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281503
telemt_connections_bad_total 10289
telemt_connections_current 802
telemt_connections_me_current 802
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2960
telemt_upstream_connect_attempt_total 6806
telemt_upstream_connect_success_total 6789
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 6806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 331609
telemt_me_reconnect_success_total 2142
telemt_me_reader_eof_total 2148
telemt_me_idle_close_by_peer_total 2148
telemt_me_route_drop_no_conn_total 182062
telemt_me_route_drop_channel_closed_total 87
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249774
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 496
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 315
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 13
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2091
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2131
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 253468
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 3610089617 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 53038177805 (49.40 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 14923.1 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 884997
telemt_connections_bad_total 57828
telemt_connections_current 3206
telemt_connections_me_current 3206
telemt_handshake_timeouts_total 15941
telemt_upstream_connect_attempt_total 2555
telemt_upstream_connect_success_total 2554
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17289
telemt_me_reconnect_success_total 1774
telemt_me_reader_eof_total 1775
telemt_me_idle_close_by_peer_total 1775
telemt_me_route_drop_no_conn_total 454484
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 749680
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3046
telemt_desync_full_logged_total 1048
telemt_desync_suppressed_total 1998
telemt_desync_frames_bucket_total{bucket="1_2"} 705
telemt_desync_frames_bucket_total{bucket="3_10"} 1096
telemt_desync_frames_bucket_total{bucket="gt_10"} 1245
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1741
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1713
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 748634
telemt_user_connections_current{user="hello"} 3206
telemt_user_octets_from_client{user="hello"} 14959804504 (13.93 GB)
telemt_user_octets_to_client{user="hello"} 398161052664 (370.82 GB)
telemt_user_unique_ips_current{user="hello"} 912
telemt_user_unique_ips_recent_window{user="hello"} 386
```