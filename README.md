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

# Server Metrics 2026-03-19 08:31:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 38583.8 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731066
telemt_connections_bad_total 74679
telemt_connections_current 1657
telemt_connections_me_current 1657
telemt_handshake_timeouts_total 26114
telemt_upstream_connect_attempt_total 7296
telemt_upstream_connect_success_total 7166
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 7296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6399
telemt_me_reconnect_success_total 5245
telemt_me_reader_eof_total 5562
telemt_me_idle_close_by_peer_total 5561
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 208909
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559823
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3592
telemt_desync_full_logged_total 1053
telemt_desync_suppressed_total 2539
telemt_desync_frames_bucket_total{bucket="1_2"} 1238
telemt_desync_frames_bucket_total{bucket="3_10"} 1333
telemt_desync_frames_bucket_total{bucket="gt_10"} 1021
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5341
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5228
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 556839
telemt_user_connections_current{user="hello"} 1657
telemt_user_octets_from_client{user="hello"} 8227198724 (7.66 GB)
telemt_user_octets_to_client{user="hello"} 185396046472 (172.66 GB)
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 38587.6 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1784183
telemt_connections_bad_total 100371
telemt_connections_current 4117
telemt_connections_me_current 4117
telemt_handshake_timeouts_total 41173
telemt_upstream_connect_attempt_total 7242
telemt_upstream_connect_success_total 7107
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 7242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 6329
telemt_me_reconnect_success_total 5172
telemt_me_reader_eof_total 5485
telemt_me_idle_close_by_peer_total 5485
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 782335
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1477034
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6566
telemt_desync_full_logged_total 2210
telemt_desync_suppressed_total 4356
telemt_desync_frames_bucket_total{bucket="1_2"} 1183
telemt_desync_frames_bucket_total{bucket="3_10"} 2484
telemt_desync_frames_bucket_total{bucket="gt_10"} 2899
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5302
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5150
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 1476836
telemt_user_connections_current{user="hello"} 4117
telemt_user_octets_from_client{user="hello"} 25423943272 (23.68 GB)
telemt_user_octets_to_client{user="hello"} 563873741668 (525.15 GB)
telemt_user_unique_ips_current{user="hello"} 1389
telemt_user_unique_ips_recent_window{user="hello"} 673
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 38585.4 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1512040
telemt_connections_bad_total 195219
telemt_connections_current 3009
telemt_connections_me_current 3009
telemt_handshake_timeouts_total 37527
telemt_upstream_connect_attempt_total 6844
telemt_upstream_connect_success_total 6844
telemt_upstream_connect_attempts_per_request{bucket="1"} 6844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 4938
telemt_me_reconnect_success_total 4909
telemt_me_reader_eof_total 5205
telemt_me_idle_close_by_peer_total 5205
telemt_me_route_drop_no_conn_total 681780
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1159447
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5496
telemt_desync_full_logged_total 1702
telemt_desync_suppressed_total 3794
telemt_desync_frames_bucket_total{bucket="1_2"} 1195
telemt_desync_frames_bucket_total{bucket="3_10"} 1973
telemt_desync_frames_bucket_total{bucket="gt_10"} 2328
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5001
telemt_me_writer_restored_same_endpoint_total 4893
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 1159019
telemt_user_connections_current{user="hello"} 3009
telemt_user_octets_from_client{user="hello"} 19192049428 (17.87 GB)
telemt_user_octets_to_client{user="hello"} 570856024472 (531.65 GB)
telemt_user_unique_ips_current{user="hello"} 1064
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 38638.1 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1582700
telemt_connections_bad_total 95181
telemt_connections_current 3069
telemt_connections_me_current 3069
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 40277
telemt_upstream_connect_attempt_total 15053
telemt_upstream_connect_success_total 14957
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 15053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7257
telemt_me_reconnect_success_total 4869
telemt_me_reader_eof_total 5175
telemt_me_idle_close_by_peer_total 5174
telemt_me_route_drop_no_conn_total 701481
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1130566
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4109
telemt_desync_full_logged_total 1403
telemt_desync_suppressed_total 2706
telemt_desync_frames_bucket_total{bucket="1_2"} 814
telemt_desync_frames_bucket_total{bucket="3_10"} 1622
telemt_desync_frames_bucket_total{bucket="gt_10"} 1673
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5122
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 4845
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 1137400
telemt_user_connections_current{user="hello"} 3069
telemt_user_octets_from_client{user="hello"} 14591111420 (13.59 GB)
telemt_user_octets_to_client{user="hello"} 357025924842 (332.51 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 998
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 38581.5 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1862157
telemt_connections_bad_total 483169
telemt_connections_current 3359
telemt_connections_me_current 3359
telemt_handshake_timeouts_total 38808
telemt_upstream_connect_attempt_total 6610
telemt_upstream_connect_success_total 6565
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 6610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4672
telemt_me_reconnect_success_total 4639
telemt_me_reader_eof_total 4922
telemt_me_idle_close_by_peer_total 4922
telemt_me_route_drop_no_conn_total 487434
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1149500
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5664
telemt_desync_full_logged_total 1758
telemt_desync_suppressed_total 3906
telemt_desync_frames_bucket_total{bucket="1_2"} 1159
telemt_desync_frames_bucket_total{bucket="3_10"} 2549
telemt_desync_frames_bucket_total{bucket="gt_10"} 1956
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 4703
telemt_me_writer_restored_same_endpoint_total 4615
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 1149121
telemt_user_connections_current{user="hello"} 3359
telemt_user_octets_from_client{user="hello"} 23013928376 (21.43 GB)
telemt_user_octets_to_client{user="hello"} 539691121032 (502.63 GB)
telemt_user_unique_ips_current{user="hello"} 1190
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 38594.4 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319463
telemt_connections_bad_total 14741
telemt_connections_current 983
telemt_connections_me_current 983
telemt_handshake_timeouts_total 2809
telemt_upstream_connect_attempt_total 9840
telemt_upstream_connect_success_total 9586
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 9840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13036
telemt_me_reconnect_success_total 7657
telemt_me_reader_eof_total 8130
telemt_me_idle_close_by_peer_total 8130
telemt_me_route_drop_no_conn_total 146984
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285786
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 409
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 266
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7878
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7627
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 285743
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 4208499312 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 126723429992 (118.02 GB)
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 38583.9 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1219537
telemt_connections_bad_total 99950
telemt_connections_current 3114
telemt_connections_me_current 3114
telemt_handshake_timeouts_total 53659
telemt_upstream_connect_attempt_total 7764
telemt_upstream_connect_success_total 7763
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 7173
telemt_me_reconnect_success_total 5831
telemt_me_reader_eof_total 6188
telemt_me_idle_close_by_peer_total 6187
telemt_me_route_drop_no_conn_total 482598
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1018877
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6049
telemt_desync_full_logged_total 1987
telemt_desync_suppressed_total 4062
telemt_desync_frames_bucket_total{bucket="1_2"} 1156
telemt_desync_frames_bucket_total{bucket="3_10"} 2271
telemt_desync_frames_bucket_total{bucket="gt_10"} 2622
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5938
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5816
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 1017832
telemt_user_connections_current{user="hello"} 3114
telemt_user_octets_from_client{user="hello"} 14246665140 (13.27 GB)
telemt_user_octets_to_client{user="hello"} 517320866624 (481.79 GB)
telemt_user_unique_ips_current{user="hello"} 991
telemt_user_unique_ips_recent_window{user="hello"} 499
```