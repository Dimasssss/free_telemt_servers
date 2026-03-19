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

# Server Metrics 2026-03-19 08:57:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 40126.4 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788485
telemt_connections_bad_total 77437
telemt_connections_current 1626
telemt_connections_me_current 1626
telemt_handshake_timeouts_total 32865
telemt_upstream_connect_attempt_total 7600
telemt_upstream_connect_success_total 7467
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 7600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 6612
telemt_me_reconnect_success_total 5458
telemt_me_reader_eof_total 5786
telemt_me_idle_close_by_peer_total 5785
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 228140
telemt_me_route_drop_channel_closed_total 93
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 603758
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3873
telemt_desync_full_logged_total 1143
telemt_desync_suppressed_total 2730
telemt_desync_frames_bucket_total{bucket="1_2"} 1300
telemt_desync_frames_bucket_total{bucket="3_10"} 1424
telemt_desync_frames_bucket_total{bucket="gt_10"} 1149
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5556
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5439
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 600757
telemt_user_connections_current{user="hello"} 1626
telemt_user_octets_from_client{user="hello"} 9757671260 (9.09 GB)
telemt_user_octets_to_client{user="hello"} 199087899544 (185.42 GB)
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 40131.4 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1932100
telemt_connections_bad_total 106678
telemt_connections_current 4323
telemt_connections_me_current 4323
telemt_handshake_timeouts_total 43950
telemt_upstream_connect_attempt_total 7608
telemt_upstream_connect_success_total 7466
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 7608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 6598
telemt_me_reconnect_success_total 5437
telemt_me_reader_eof_total 5753
telemt_me_idle_close_by_peer_total 5753
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 841324
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1601375
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7046
telemt_desync_full_logged_total 2404
telemt_desync_suppressed_total 4642
telemt_desync_frames_bucket_total{bucket="1_2"} 1261
telemt_desync_frames_bucket_total{bucket="3_10"} 2693
telemt_desync_frames_bucket_total{bucket="gt_10"} 3092
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5571
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5415
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 1601141
telemt_user_connections_current{user="hello"} 4323
telemt_user_octets_from_client{user="hello"} 27093259184 (25.23 GB)
telemt_user_octets_to_client{user="hello"} 603816328268 (562.35 GB)
telemt_user_unique_ips_current{user="hello"} 1422
telemt_user_unique_ips_recent_window{user="hello"} 637
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 40128.4 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1634868
telemt_connections_bad_total 203713
telemt_connections_current 3225
telemt_connections_me_current 3225
telemt_handshake_timeouts_total 40330
telemt_upstream_connect_attempt_total 7162
telemt_upstream_connect_success_total 7162
telemt_upstream_connect_attempts_per_request{bucket="1"} 7162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 5164
telemt_me_reconnect_success_total 5133
telemt_me_reader_eof_total 5438
telemt_me_idle_close_by_peer_total 5438
telemt_me_route_drop_no_conn_total 746039
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1260575
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5853
telemt_desync_full_logged_total 1825
telemt_desync_suppressed_total 4028
telemt_desync_frames_bucket_total{bucket="1_2"} 1308
telemt_desync_frames_bucket_total{bucket="3_10"} 2117
telemt_desync_frames_bucket_total{bucket="gt_10"} 2428
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5225
telemt_me_writer_restored_same_endpoint_total 5117
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 1260060
telemt_user_connections_current{user="hello"} 3225
telemt_user_octets_from_client{user="hello"} 20340408432 (18.94 GB)
telemt_user_octets_to_client{user="hello"} 603951240444 (562.47 GB)
telemt_user_unique_ips_current{user="hello"} 1103
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 40182.1 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1685007
telemt_connections_bad_total 97005
telemt_connections_current 2983
telemt_connections_me_current 2983
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 43568
telemt_upstream_connect_attempt_total 15390
telemt_upstream_connect_success_total 15288
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 15390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7504
telemt_me_reconnect_success_total 5109
telemt_me_reader_eof_total 5431
telemt_me_idle_close_by_peer_total 5430
telemt_me_route_drop_no_conn_total 752340
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1221648
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4515
telemt_desync_full_logged_total 1550
telemt_desync_suppressed_total 2965
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1777
telemt_desync_frames_bucket_total{bucket="gt_10"} 1837
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5368
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5085
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 1228429
telemt_user_connections_current{user="hello"} 2983
telemt_user_octets_from_client{user="hello"} 15603237224 (14.53 GB)
telemt_user_octets_to_client{user="hello"} 380984934946 (354.82 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1007
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 40124.9 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2001590
telemt_connections_bad_total 508763
telemt_connections_current 3575
telemt_connections_me_current 3575
telemt_handshake_timeouts_total 42075
telemt_upstream_connect_attempt_total 6881
telemt_upstream_connect_success_total 6832
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 6881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 4853
telemt_me_reconnect_success_total 4812
telemt_me_reader_eof_total 5104
telemt_me_idle_close_by_peer_total 5104
telemt_me_route_drop_no_conn_total 540970
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1250739
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6075
telemt_desync_full_logged_total 1894
telemt_desync_suppressed_total 4181
telemt_desync_frames_bucket_total{bucket="1_2"} 1224
telemt_desync_frames_bucket_total{bucket="3_10"} 2701
telemt_desync_frames_bucket_total{bucket="gt_10"} 2150
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 4883
telemt_me_writer_restored_same_endpoint_total 4788
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1250008
telemt_user_connections_current{user="hello"} 3575
telemt_user_octets_from_client{user="hello"} 24481369108 (22.80 GB)
telemt_user_octets_to_client{user="hello"} 572348316784 (533.04 GB)
telemt_user_unique_ips_current{user="hello"} 1198
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 40136.9 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345698
telemt_connections_bad_total 14969
telemt_connections_current 841
telemt_connections_me_current 841
telemt_handshake_timeouts_total 2916
telemt_upstream_connect_attempt_total 10230
telemt_upstream_connect_success_total 9966
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 10230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13326
telemt_me_reconnect_success_total 7944
telemt_me_reader_eof_total 8437
telemt_me_idle_close_by_peer_total 8437
telemt_me_route_drop_no_conn_total 160252
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309440
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 484
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 316
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 193
telemt_me_writer_removed_unexpected_total 8171
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7914
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 309405
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 4526176840 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 133312255560 (124.16 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 40127.4 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1338757
telemt_connections_bad_total 118475
telemt_connections_current 3032
telemt_connections_me_current 3032
telemt_handshake_timeouts_total 59165
telemt_upstream_connect_attempt_total 8087
telemt_upstream_connect_success_total 8086
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 7409
telemt_me_reconnect_success_total 6063
telemt_me_reader_eof_total 6427
telemt_me_idle_close_by_peer_total 6426
telemt_me_route_drop_no_conn_total 520946
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1109550
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6454
telemt_desync_full_logged_total 2122
telemt_desync_suppressed_total 4332
telemt_desync_frames_bucket_total{bucket="1_2"} 1212
telemt_desync_frames_bucket_total{bucket="3_10"} 2442
telemt_desync_frames_bucket_total{bucket="gt_10"} 2800
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6175
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6048
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 1108456
telemt_user_connections_current{user="hello"} 3032
telemt_user_octets_from_client{user="hello"} 15406709552 (14.35 GB)
telemt_user_octets_to_client{user="hello"} 553703596684 (515.68 GB)
telemt_user_unique_ips_current{user="hello"} 998
telemt_user_unique_ips_recent_window{user="hello"} 413
```