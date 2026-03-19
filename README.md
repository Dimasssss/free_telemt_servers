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

# Server Metrics 2026-03-19 08:16:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 37665.8 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700232
telemt_connections_bad_total 71964
telemt_connections_current 1535
telemt_connections_me_current 1535
telemt_handshake_timeouts_total 25433
telemt_upstream_connect_attempt_total 7106
telemt_upstream_connect_success_total 6976
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 7106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6253
telemt_me_reconnect_success_total 5100
telemt_me_reader_eof_total 5417
telemt_me_idle_close_by_peer_total 5416
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 199743
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534270
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3496
telemt_desync_full_logged_total 1008
telemt_desync_suppressed_total 2488
telemt_desync_frames_bucket_total{bucket="1_2"} 1218
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 975
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5196
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5083
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 531294
telemt_user_connections_current{user="hello"} 1535
telemt_user_octets_from_client{user="hello"} 7218896280 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 176465718472 (164.35 GB)
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 37670.4 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1700724
telemt_connections_bad_total 97824
telemt_connections_current 4201
telemt_connections_me_current 4201
telemt_handshake_timeouts_total 40000
telemt_upstream_connect_attempt_total 7109
telemt_upstream_connect_success_total 6976
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 7109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 6242
telemt_me_reconnect_success_total 5085
telemt_me_reader_eof_total 5391
telemt_me_idle_close_by_peer_total 5391
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 752576
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1402705
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6201
telemt_desync_full_logged_total 2070
telemt_desync_suppressed_total 4131
telemt_desync_frames_bucket_total{bucket="1_2"} 1100
telemt_desync_frames_bucket_total{bucket="3_10"} 2359
telemt_desync_frames_bucket_total{bucket="gt_10"} 2742
telemt_pool_swap_total 30
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5213
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5064
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1402489
telemt_user_connections_current{user="hello"} 4201
telemt_user_octets_from_client{user="hello"} 24231456936 (22.57 GB)
telemt_user_octets_to_client{user="hello"} 539664656512 (502.60 GB)
telemt_user_unique_ips_current{user="hello"} 1417
telemt_user_unique_ips_recent_window{user="hello"} 703
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 37667.6 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1443102
telemt_connections_bad_total 190042
telemt_connections_current 3076
telemt_connections_me_current 3076
telemt_handshake_timeouts_total 36661
telemt_upstream_connect_attempt_total 6703
telemt_upstream_connect_success_total 6703
telemt_upstream_connect_attempts_per_request{bucket="1"} 6703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 4841
telemt_me_reconnect_success_total 4813
telemt_me_reader_eof_total 5097
telemt_me_idle_close_by_peer_total 5097
telemt_me_route_drop_no_conn_total 655786
telemt_me_route_drop_channel_closed_total 49
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1104324
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5209
telemt_desync_full_logged_total 1607
telemt_desync_suppressed_total 3602
telemt_desync_frames_bucket_total{bucket="1_2"} 1118
telemt_desync_frames_bucket_total{bucket="3_10"} 1861
telemt_desync_frames_bucket_total{bucket="gt_10"} 2230
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 4903
telemt_me_writer_restored_same_endpoint_total 4797
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 1103909
telemt_user_connections_current{user="hello"} 3076
telemt_user_octets_from_client{user="hello"} 18658055092 (17.38 GB)
telemt_user_octets_to_client{user="hello"} 549347369036 (511.62 GB)
telemt_user_unique_ips_current{user="hello"} 1055
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 37720.6 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1500539
telemt_connections_bad_total 93456
telemt_connections_current 3177
telemt_connections_me_current 3177
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 37508
telemt_upstream_connect_attempt_total 14928
telemt_upstream_connect_success_total 14832
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 14928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7175
telemt_me_reconnect_success_total 4787
telemt_me_reader_eof_total 5091
telemt_me_idle_close_by_peer_total 5090
telemt_me_route_drop_no_conn_total 635087
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1058744
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3818
telemt_desync_full_logged_total 1315
telemt_desync_suppressed_total 2503
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 1509
telemt_desync_frames_bucket_total{bucket="gt_10"} 1570
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5040
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 4763
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 1065615
telemt_user_connections_current{user="hello"} 3177
telemt_user_octets_from_client{user="hello"} 14051368084 (13.09 GB)
telemt_user_octets_to_client{user="hello"} 344723163766 (321.05 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 974
telemt_user_unique_ips_recent_window{user="hello"} 549
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 37664.0 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1774451
telemt_connections_bad_total 462659
telemt_connections_current 3472
telemt_connections_me_current 3472
telemt_handshake_timeouts_total 37202
telemt_upstream_connect_attempt_total 6495
telemt_upstream_connect_success_total 6451
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 6495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4601
telemt_me_reconnect_success_total 4568
telemt_me_reader_eof_total 4845
telemt_me_idle_close_by_peer_total 4845
telemt_me_route_drop_no_conn_total 458333
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1090428
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5284
telemt_desync_full_logged_total 1641
telemt_desync_suppressed_total 3643
telemt_desync_frames_bucket_total{bucket="1_2"} 1083
telemt_desync_frames_bucket_total{bucket="3_10"} 2386
telemt_desync_frames_bucket_total{bucket="gt_10"} 1815
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 4630
telemt_me_writer_restored_same_endpoint_total 4544
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1090079
telemt_user_connections_current{user="hello"} 3472
telemt_user_octets_from_client{user="hello"} 22064340936 (20.55 GB)
telemt_user_octets_to_client{user="hello"} 517004520788 (481.50 GB)
telemt_user_unique_ips_current{user="hello"} 1158
telemt_user_unique_ips_recent_window{user="hello"} 517
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 37676.6 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302822
telemt_connections_bad_total 14627
telemt_connections_current 905
telemt_connections_me_current 905
telemt_handshake_timeouts_total 2758
telemt_upstream_connect_attempt_total 9649
telemt_upstream_connect_success_total 9403
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 9649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 12897
telemt_me_reconnect_success_total 7520
telemt_me_reader_eof_total 7990
telemt_me_idle_close_by_peer_total 7990
telemt_me_route_drop_no_conn_total 139944
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270273
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 263
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7739
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7490
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 270239
telemt_user_connections_current{user="hello"} 905
telemt_user_octets_from_client{user="hello"} 4056835388 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 123773219104 (115.27 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 37666.4 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1154606
telemt_connections_bad_total 97404
telemt_connections_current 3232
telemt_connections_me_current 3232
telemt_handshake_timeouts_total 50732
telemt_upstream_connect_attempt_total 7601
telemt_upstream_connect_success_total 7600
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7053
telemt_me_reconnect_success_total 5712
telemt_me_reader_eof_total 6056
telemt_me_idle_close_by_peer_total 6055
telemt_me_route_drop_no_conn_total 458885
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 962659
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5716
telemt_desync_full_logged_total 1878
telemt_desync_suppressed_total 3838
telemt_desync_frames_bucket_total{bucket="1_2"} 1115
telemt_desync_frames_bucket_total{bucket="3_10"} 2138
telemt_desync_frames_bucket_total{bucket="gt_10"} 2463
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5818
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5697
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 961642
telemt_user_connections_current{user="hello"} 3232
telemt_user_octets_from_client{user="hello"} 13587651932 (12.65 GB)
telemt_user_octets_to_client{user="hello"} 495770775868 (461.72 GB)
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 449
```