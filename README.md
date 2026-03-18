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

# Server Metrics 2026-03-18 07:08:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 130973.2 (36h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1728097
telemt_connections_bad_total 11615
telemt_handshake_timeouts_total 37157
telemt_upstream_connect_attempt_total 28375
telemt_upstream_connect_success_total 27852
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 28375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 36201
telemt_me_reconnect_success_total 19041
telemt_me_reader_eof_total 20626
telemt_me_idle_close_by_peer_total 20625
telemt_me_route_drop_no_conn_total 648832
telemt_me_route_drop_channel_closed_total 186
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1423178
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8561
telemt_desync_full_logged_total 2590
telemt_desync_suppressed_total 5971
telemt_desync_frames_bucket_total{bucket="1_2"} 2214
telemt_desync_frames_bucket_total{bucket="3_10"} 3303
telemt_desync_frames_bucket_total{bucket="gt_10"} 3044
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19863
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19019
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 822
telemt_user_connections_total{user="hello"} 1417427
telemt_user_connections_current{user="hello"} 1165
telemt_user_octets_from_client{user="hello"} 32951708711 (30.69 GB)
telemt_user_octets_to_client{user="hello"} 506566462843 (471.78 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 131225.3 (36h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1819981
telemt_connections_bad_total 93852
telemt_handshake_timeouts_total 57971
telemt_upstream_connect_attempt_total 471958
telemt_upstream_connect_success_total 470313
telemt_upstream_connect_fail_total 1645
telemt_upstream_connect_attempts_per_request{bucket="1"} 471958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1645
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 128793
telemt_me_reconnect_success_total 20874
telemt_me_reader_eof_total 23227
telemt_me_idle_close_by_peer_total 23214
telemt_me_route_drop_no_conn_total 504897
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1140312
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5235
telemt_desync_full_logged_total 1826
telemt_desync_suppressed_total 3409
telemt_desync_frames_bucket_total{bucket="1_2"} 982
telemt_desync_frames_bucket_total{bucket="3_10"} 2124
telemt_desync_frames_bucket_total{bucket="gt_10"} 2129
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22550
telemt_me_refill_failed_total 3366
telemt_me_writer_restored_same_endpoint_total 20856
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1676
telemt_user_connections_total{user="hello"} 1582652
telemt_user_connections_current{user="hello"} 2452
telemt_user_octets_from_client{user="hello"} 24203741221 (22.54 GB)
telemt_user_octets_to_client{user="hello"} 621273554502 (578.61 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 780
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 131001.0 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1327336
telemt_connections_bad_total 82994
telemt_handshake_timeouts_total 32289
telemt_upstream_connect_attempt_total 29627
telemt_upstream_connect_success_total 29461
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 29627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 43606
telemt_me_reconnect_success_total 22888
telemt_me_reader_eof_total 24858
telemt_me_idle_close_by_peer_total 24850
telemt_me_route_drop_no_conn_total 497593
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 984908
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3420
telemt_desync_full_logged_total 1115
telemt_desync_suppressed_total 2305
telemt_desync_frames_bucket_total{bucket="1_2"} 917
telemt_desync_frames_bucket_total{bucket="3_10"} 1312
telemt_desync_frames_bucket_total{bucket="gt_10"} 1191
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23855
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22876
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 967
telemt_user_connections_total{user="hello"} 982960
telemt_user_connections_current{user="hello"} 1520
telemt_user_octets_from_client{user="hello"} 48777809540 (45.43 GB)
telemt_user_octets_to_client{user="hello"} 475674619504 (443.01 GB)
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 131060.3 (36h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1711726
telemt_connections_bad_total 84253
telemt_handshake_timeouts_total 30489
telemt_upstream_connect_attempt_total 92741
telemt_upstream_connect_success_total 90286
telemt_upstream_connect_fail_total 2455
telemt_upstream_connect_attempts_per_request{bucket="1"} 92741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 385
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2455
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 39426
telemt_me_reconnect_success_total 18997
telemt_me_reader_eof_total 20801
telemt_me_idle_close_by_peer_total 20798
telemt_me_route_drop_no_conn_total 700396
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1411624
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5484
telemt_desync_full_logged_total 1743
telemt_desync_suppressed_total 3741
telemt_desync_frames_bucket_total{bucket="1_2"} 1284
telemt_desync_frames_bucket_total{bucket="3_10"} 2243
telemt_desync_frames_bucket_total{bucket="gt_10"} 1957
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19989
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18977
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 992
telemt_user_connections_total{user="hello"} 1474834
telemt_user_connections_current{user="hello"} 2400
telemt_user_octets_from_client{user="hello"} 24296056698 (22.63 GB)
telemt_user_octets_to_client{user="hello"} 695629214458 (647.86 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 131032.0 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1236484
telemt_connections_bad_total 110837
telemt_handshake_timeouts_total 13173
telemt_upstream_connect_attempt_total 49728
telemt_upstream_connect_success_total 49041
telemt_upstream_connect_fail_total 687
telemt_upstream_connect_attempts_per_request{bucket="1"} 49728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 431
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 687
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 63547
telemt_me_reconnect_success_total 26045
telemt_me_reader_eof_total 28207
telemt_me_idle_close_by_peer_total 28204
telemt_me_route_drop_no_conn_total 408030
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1019391
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4404
telemt_desync_full_logged_total 1365
telemt_desync_suppressed_total 3039
telemt_desync_frames_bucket_total{bucket="1_2"} 1174
telemt_desync_frames_bucket_total{bucket="3_10"} 1697
telemt_desync_frames_bucket_total{bucket="gt_10"} 1533
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27618
telemt_me_refill_failed_total 1166
telemt_me_writer_restored_same_endpoint_total 26037
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1573
telemt_user_connections_total{user="hello"} 1035766
telemt_user_connections_current{user="hello"} 1975
telemt_user_octets_from_client{user="hello"} 20083195300 (18.70 GB)
telemt_user_octets_to_client{user="hello"} 518959975840 (483.32 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 638
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 131193.2 (36h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280001
telemt_connections_bad_total 133901
telemt_handshake_timeouts_total 10915
telemt_upstream_connect_attempt_total 26128
telemt_upstream_connect_success_total 25972
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 26128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 30768
telemt_me_reconnect_success_total 19465
telemt_me_reader_eof_total 21054
telemt_me_idle_close_by_peer_total 21051
telemt_me_route_drop_no_conn_total 851962
telemt_me_route_drop_channel_closed_total 96
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1249038
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2455
telemt_desync_full_logged_total 864
telemt_desync_suppressed_total 1591
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 942
telemt_desync_frames_bucket_total{bucket="gt_10"} 967
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20115
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19451
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 650
telemt_user_connections_total{user="hello"} 1057693
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 16515086436 (15.38 GB)
telemt_user_octets_to_client{user="hello"} 466393815780 (434.36 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 78960.4 (21h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694775
telemt_connections_bad_total 59698
telemt_handshake_timeouts_total 15098
telemt_upstream_connect_attempt_total 26611
telemt_upstream_connect_success_total 26330
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 26611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 33886
telemt_me_reconnect_success_total 22266
telemt_me_reader_eof_total 23528
telemt_me_idle_close_by_peer_total 23528
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 199186
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524270
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2215
telemt_desync_full_logged_total 760
telemt_desync_suppressed_total 1455
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 953
telemt_desync_frames_bucket_total{bucket="gt_10"} 897
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22870
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22219
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 604
telemt_user_connections_total{user="hello"} 523968
telemt_user_connections_current{user="hello"} 1447
telemt_user_octets_from_client{user="hello"} 28094234833 (26.16 GB)
telemt_user_octets_to_client{user="hello"} 384650209282 (358.23 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 196
```