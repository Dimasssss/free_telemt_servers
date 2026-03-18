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

# Server Metrics 2026-03-18 05:26:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 124863.8 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1463149
telemt_connections_bad_total 10581
telemt_handshake_timeouts_total 35229
telemt_upstream_connect_attempt_total 27221
telemt_upstream_connect_success_total 26704
telemt_upstream_connect_fail_total 517
telemt_upstream_connect_attempts_per_request{bucket="1"} 27221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 517
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 35360
telemt_me_reconnect_success_total 18212
telemt_me_reader_eof_total 19752
telemt_me_idle_close_by_peer_total 19751
telemt_me_route_drop_no_conn_total 608796
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1319705
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8117
telemt_desync_full_logged_total 2437
telemt_desync_suppressed_total 5680
telemt_desync_frames_bucket_total{bucket="1_2"} 2134
telemt_desync_frames_bucket_total{bucket="3_10"} 3115
telemt_desync_frames_bucket_total{bucket="gt_10"} 2868
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 19020
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18190
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 808
telemt_user_connections_total{user="hello"} 1313936
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 31202003335 (29.06 GB)
telemt_user_octets_to_client{user="hello"} 468086887099 (435.94 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 125115.8 (34h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1576053
telemt_connections_bad_total 75456
telemt_handshake_timeouts_total 52012
telemt_upstream_connect_attempt_total 470657
telemt_upstream_connect_success_total 469031
telemt_upstream_connect_fail_total 1626
telemt_upstream_connect_attempts_per_request{bucket="1"} 470657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1626
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126634
telemt_me_reconnect_success_total 19905
telemt_me_reader_eof_total 22191
telemt_me_idle_close_by_peer_total 22178
telemt_me_route_drop_no_conn_total 412969
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 930631
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4151
telemt_desync_full_logged_total 1443
telemt_desync_suppressed_total 2708
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 1691
telemt_desync_frames_bucket_total{bucket="gt_10"} 1640
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 21531
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19887
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1626
telemt_user_connections_total{user="hello"} 1372981
telemt_user_connections_current{user="hello"} 1554
telemt_user_octets_from_client{user="hello"} 18912254301 (17.61 GB)
telemt_user_octets_to_client{user="hello"} 519552225034 (483.87 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 124892.2 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1032631
telemt_connections_bad_total 71315
telemt_handshake_timeouts_total 28389
telemt_upstream_connect_attempt_total 28599
telemt_upstream_connect_success_total 28438
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 28599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42890
telemt_me_reconnect_success_total 22188
telemt_me_reader_eof_total 24116
telemt_me_idle_close_by_peer_total 24109
telemt_me_route_drop_no_conn_total 374018
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 827550
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2772
telemt_desync_full_logged_total 909
telemt_desync_suppressed_total 1863
telemt_desync_frames_bucket_total{bucket="1_2"} 761
telemt_desync_frames_bucket_total{bucket="3_10"} 1078
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 23133
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22176
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 825652
telemt_user_connections_current{user="hello"} 1257
telemt_user_octets_from_client{user="hello"} 45831834536 (42.68 GB)
telemt_user_octets_to_client{user="hello"} 396124786204 (368.92 GB)
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 124951.1 (34h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1466403
telemt_connections_bad_total 72213
telemt_handshake_timeouts_total 25022
telemt_upstream_connect_attempt_total 91591
telemt_upstream_connect_success_total 89148
telemt_upstream_connect_fail_total 2443
telemt_upstream_connect_attempts_per_request{bucket="1"} 91591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2443
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38593
telemt_me_reconnect_success_total 18177
telemt_me_reader_eof_total 19946
telemt_me_idle_close_by_peer_total 19943
telemt_me_route_drop_no_conn_total 592235
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1196183
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4614
telemt_desync_full_logged_total 1504
telemt_desync_suppressed_total 3110
telemt_desync_frames_bucket_total{bucket="1_2"} 1103
telemt_desync_frames_bucket_total{bucket="3_10"} 1922
telemt_desync_frames_bucket_total{bucket="gt_10"} 1589
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 19153
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18157
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 976
telemt_user_connections_total{user="hello"} 1259459
telemt_user_connections_current{user="hello"} 1502
telemt_user_octets_from_client{user="hello"} 20581596430 (19.17 GB)
telemt_user_octets_to_client{user="hello"} 616159995690 (573.84 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 124923.1 (34h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1027493
telemt_connections_bad_total 103985
telemt_handshake_timeouts_total 10008
telemt_upstream_connect_attempt_total 48595
telemt_upstream_connect_success_total 47925
telemt_upstream_connect_fail_total 670
telemt_upstream_connect_attempts_per_request{bucket="1"} 48595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 670
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60209
telemt_me_reconnect_success_total 25243
telemt_me_reader_eof_total 27304
telemt_me_idle_close_by_peer_total 27301
telemt_me_route_drop_no_conn_total 330120
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 841006
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3711
telemt_desync_full_logged_total 1136
telemt_desync_suppressed_total 2575
telemt_desync_frames_bucket_total{bucket="1_2"} 1084
telemt_desync_frames_bucket_total{bucket="3_10"} 1442
telemt_desync_frames_bucket_total{bucket="gt_10"} 1185
telemt_pool_swap_total 66
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26722
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25235
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1479
telemt_user_connections_total{user="hello"} 857480
telemt_user_connections_current{user="hello"} 1370
telemt_user_octets_from_client{user="hello"} 16454988288 (15.32 GB)
telemt_user_octets_to_client{user="hello"} 433844053784 (404.05 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 125084.1 (34h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1201258
telemt_connections_bad_total 127481
telemt_handshake_timeouts_total 10491
telemt_upstream_connect_attempt_total 24864
telemt_upstream_connect_success_total 24719
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 24864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29819
telemt_me_reconnect_success_total 18525
telemt_me_reader_eof_total 20072
telemt_me_idle_close_by_peer_total 20070
telemt_me_route_drop_no_conn_total 822504
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1180521
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2258
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1471
telemt_desync_frames_bucket_total{bucket="1_2"} 504
telemt_desync_frames_bucket_total{bucket="3_10"} 858
telemt_desync_frames_bucket_total{bucket="gt_10"} 896
telemt_pool_swap_total 113
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19163
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18511
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 989202
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 15694399936 (14.62 GB)
telemt_user_octets_to_client{user="hello"} 441225928960 (410.92 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 72851.4 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553439
telemt_connections_bad_total 54289
telemt_handshake_timeouts_total 13366
telemt_upstream_connect_attempt_total 25465
telemt_upstream_connect_success_total 25204
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 25465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33062
telemt_me_reconnect_success_total 21448
telemt_me_reader_eof_total 22665
telemt_me_idle_close_by_peer_total 22665
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 135682
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400646
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1736
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 671
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22038
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21405
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 590
telemt_user_connections_total{user="hello"} 400401
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 24999206981 (23.28 GB)
telemt_user_octets_to_client{user="hello"} 313860266350 (292.31 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 111
```