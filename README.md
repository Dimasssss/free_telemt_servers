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

# Server Metrics 2026-03-12 16:53:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33630.9 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176533
telemt_connections_bad_total 2041
telemt_handshake_timeouts_total 4876
telemt_upstream_connect_attempt_total 8381
telemt_upstream_connect_success_total 8349
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 8381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 333
telemt_me_reconnect_attempts_total 7743
telemt_me_reconnect_success_total 6605
telemt_me_reader_eof_total 6968
telemt_me_idle_close_by_peer_total 6967
telemt_me_route_drop_no_conn_total 51580
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 624
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6707
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6589
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 150676
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 2554128400 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 60492644776 (56.34 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33524.3 (9h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74605
telemt_connections_bad_total 466
telemt_handshake_timeouts_total 623
telemt_upstream_connect_attempt_total 10642
telemt_upstream_connect_success_total 10420
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 10642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 32961
telemt_me_reconnect_success_total 8705
telemt_me_reader_eof_total 9631
telemt_me_idle_close_by_peer_total 9631
telemt_me_route_drop_no_conn_total 32714
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70850
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 9529
telemt_me_refill_failed_total 757
telemt_me_writer_restored_same_endpoint_total 8690
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 824
telemt_user_connections_total{user="hello"} 70835
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 787895108 (751.40 MB)
telemt_user_octets_to_client{user="hello"} 19637618740 (18.29 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33487.6 (9h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100248
telemt_connections_bad_total 1493
telemt_handshake_timeouts_total 2047
telemt_upstream_connect_attempt_total 9341
telemt_upstream_connect_success_total 9341
telemt_upstream_connect_attempts_per_request{bucket="1"} 9341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4803
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 174
telemt_me_reconnect_attempts_total 7638
telemt_me_reconnect_success_total 7569
telemt_me_reader_eof_total 8018
telemt_me_idle_close_by_peer_total 8018
telemt_me_route_drop_no_conn_total 37017
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92596
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7639
telemt_me_writer_restored_same_endpoint_total 7549
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 92570
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 2260934776 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 47611049212 (44.34 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33463.3 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137703
telemt_connections_bad_total 13065
telemt_handshake_timeouts_total 1038
telemt_upstream_connect_attempt_total 7348
telemt_upstream_connect_success_total 7115
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 7348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 325
telemt_me_reconnect_attempts_total 32401
telemt_me_reconnect_success_total 5403
telemt_me_reader_eof_total 6379
telemt_me_idle_close_by_peer_total 6379
telemt_me_route_drop_no_conn_total 49216
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116571
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6308
telemt_me_refill_failed_total 842
telemt_me_writer_restored_same_endpoint_total 5395
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 905
telemt_user_connections_total{user="hello"} 116451
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 2148527508 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 50238520500 (46.79 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33432.6 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81671
telemt_connections_bad_total 8829
telemt_handshake_timeouts_total 1129
telemt_upstream_connect_attempt_total 41239
telemt_upstream_connect_success_total 40824
telemt_upstream_connect_fail_total 414
telemt_upstream_connect_attempts_per_request{bucket="1"} 41238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 414
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 45306
telemt_me_reconnect_success_total 3693
telemt_me_reader_eof_total 4988
telemt_me_idle_close_by_peer_total 4988
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12994
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34443
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5016
telemt_me_refill_failed_total 1303
telemt_me_writer_restored_same_endpoint_total 3676
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1323
telemt_user_connections_total{user="hello"} 69858
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 654577041 (624.25 MB)
telemt_user_octets_to_client{user="hello"} 20928871541 (19.49 GB)
telemt_user_msgs_from_client{user="hello"} 572938
telemt_user_msgs_to_client{user="hello"} 2129154
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33420.8 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211943
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 1714
telemt_upstream_connect_attempt_total 7156
telemt_upstream_connect_success_total 7118
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 7155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 401
telemt_me_reconnect_attempts_total 6463
telemt_me_reconnect_success_total 5395
telemt_me_reader_eof_total 5690
telemt_me_idle_close_by_peer_total 5689
telemt_me_route_drop_no_conn_total 92611
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209955
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5499
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5388
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 202367
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 3749684924 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 92229380508 (85.90 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 58
```