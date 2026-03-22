# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 18:32:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 77167.4 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2819230
telemt_connections_bad_total 176304
telemt_connections_current 1578
telemt_connections_me_current 1578
telemt_handshake_timeouts_total 95920
telemt_upstream_connect_attempt_total 28278
telemt_upstream_connect_success_total 28277
telemt_upstream_connect_attempts_per_request{bucket="1"} 28277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1148
telemt_me_reconnect_success_total 480
telemt_me_reader_eof_total 485
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 2319205
telemt_me_route_drop_channel_closed_total 970
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2388728
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 519
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 601
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 10765
telemt_desync_full_logged_total 3413
telemt_desync_suppressed_total 7352
telemt_desync_frames_bucket_total{bucket="1_2"} 2890
telemt_desync_frames_bucket_total{bucket="3_10"} 3991
telemt_desync_frames_bucket_total{bucket="gt_10"} 3884
telemt_pool_swap_total 85
telemt_pool_force_close_total 2639
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 547
telemt_me_draining_writers_reap_progress_total 25827
telemt_me_writer_removed_unexpected_total 471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1889
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24167
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2586
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23188
telemt_me_writer_teardown_success_total{mode="normal"} 26056
telemt_me_writer_teardown_noop_total 25837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 262.335852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 547
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 2384806
telemt_user_connections_current{user="hello"} 1578
telemt_user_octets_from_client{user="hello"} 35107998540 (32.70 GB)
telemt_user_octets_to_client{user="hello"} 633088685624 (589.61 GB)
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 90533.6 (25h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3747214
telemt_connections_bad_total 336761
telemt_connections_current 768
telemt_connections_me_current 768
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 95291
telemt_upstream_connect_attempt_total 55530
telemt_upstream_connect_success_total 54847
telemt_upstream_connect_fail_total 601
telemt_upstream_connect_attempts_per_request{bucket="1"} 55448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 601
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6360
telemt_me_reconnect_success_total 2334
telemt_me_reader_eof_total 2266
telemt_me_idle_close_by_peer_total 2266
telemt_me_route_drop_no_conn_total 3578594
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2976786
telemt_me_endpoint_quarantine_total 711
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 699
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 11804
telemt_desync_full_logged_total 6593
telemt_desync_suppressed_total 5211
telemt_desync_frames_bucket_total{bucket="1_2"} 2720
telemt_desync_frames_bucket_total{bucket="3_10"} 4616
telemt_desync_frames_bucket_total{bucket="gt_10"} 4468
telemt_pool_swap_total 85
telemt_pool_force_close_total 2572
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 36025
telemt_me_writer_removed_unexpected_total 2217
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4281
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33972
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33453
telemt_me_writer_teardown_success_total{mode="normal"} 38253
telemt_me_writer_teardown_noop_total 36025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.330938
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 2022
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 2987625
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 38606456563 (35.96 GB)
telemt_user_octets_to_client{user="hello"} 692306180990 (644.76 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 165393.5 (45h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15724055
telemt_connections_bad_total 1509811
telemt_connections_current 2223
telemt_connections_me_current 2223
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 388609
telemt_upstream_connect_attempt_total 73924
telemt_upstream_connect_success_total 73827
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 73844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2753
telemt_me_reconnect_success_total 1408
telemt_me_reader_eof_total 1347
telemt_me_idle_close_by_peer_total 1345
telemt_me_route_drop_no_conn_total 13911248
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12530940
telemt_me_endpoint_quarantine_total 1042
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1231
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 51539
telemt_desync_full_logged_total 16202
telemt_desync_suppressed_total 35337
telemt_desync_frames_bucket_total{bucket="1_2"} 11504
telemt_desync_frames_bucket_total{bucket="3_10"} 20083
telemt_desync_frames_bucket_total{bucket="gt_10"} 19952
telemt_pool_swap_total 178
telemt_pool_force_close_total 6026
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 972
telemt_me_draining_writers_reap_progress_total 54277
telemt_me_writer_removed_unexpected_total 1301
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4752
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50117
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5561
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 465
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48251
telemt_me_writer_teardown_success_total{mode="normal"} 54869
telemt_me_writer_teardown_noop_total 54327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109196
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.760160
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109196
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 972
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12531692
telemt_user_connections_current{user="hello"} 2223
telemt_user_octets_from_client{user="hello"} 182147249489 (169.64 GB)
telemt_user_octets_to_client{user="hello"} 3284743555427 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 881
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 165395.0 (45h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11348140
telemt_connections_bad_total 1121240
telemt_connections_current 1726
telemt_connections_me_current 1726
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 339312
telemt_upstream_connect_attempt_total 86428
telemt_upstream_connect_success_total 85226
telemt_upstream_connect_fail_total 840
telemt_upstream_connect_attempts_per_request{bucket="1"} 86066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 840
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4095
telemt_me_reconnect_success_total 1691
telemt_me_reader_eof_total 1559
telemt_me_idle_close_by_peer_total 1559
telemt_me_route_drop_no_conn_total 4442047
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8452720
telemt_me_endpoint_quarantine_total 1046
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1250
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 37597
telemt_desync_full_logged_total 12652
telemt_desync_suppressed_total 24945
telemt_desync_frames_bucket_total{bucket="1_2"} 9260
telemt_desync_frames_bucket_total{bucket="3_10"} 14481
telemt_desync_frames_bucket_total{bucket="gt_10"} 13856
telemt_pool_swap_total 175
telemt_pool_force_close_total 5443
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 690
telemt_me_draining_writers_reap_progress_total 52753
telemt_me_writer_removed_unexpected_total 1598
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4876
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49319
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4945
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47310
telemt_me_writer_teardown_success_total{mode="normal"} 54195
telemt_me_writer_teardown_noop_total 52776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106971
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.803199
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106971
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 690
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 1447
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 8391118
telemt_user_connections_current{user="hello"} 1726
telemt_user_octets_from_client{user="hello"} 210135736721 (195.70 GB)
telemt_user_octets_to_client{user="hello"} 3784676267694 (3.44 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 657
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 165360.3 (45h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10680629
telemt_connections_bad_total 920078
telemt_connections_current 1316
telemt_connections_me_current 1316
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342249
telemt_upstream_connect_attempt_total 71536
telemt_upstream_connect_success_total 70504
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 70687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4886
telemt_me_reconnect_success_total 1962
telemt_me_reader_eof_total 1715
telemt_me_idle_close_by_peer_total 1714
telemt_me_route_drop_no_conn_total 5212923
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8066625
telemt_me_endpoint_quarantine_total 1122
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1215
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 37126
telemt_desync_full_logged_total 12278
telemt_desync_suppressed_total 24848
telemt_desync_frames_bucket_total{bucket="1_2"} 9400
telemt_desync_frames_bucket_total{bucket="3_10"} 14213
telemt_desync_frames_bucket_total{bucket="gt_10"} 13513
telemt_pool_swap_total 173
telemt_pool_force_close_total 5376
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 699
telemt_me_draining_writers_reap_progress_total 52975
telemt_me_writer_removed_unexpected_total 1856
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5316
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49432
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4831
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47599
telemt_me_writer_teardown_success_total{mode="normal"} 54748
telemt_me_writer_teardown_noop_total 53046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107794
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.507432
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107794
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 699
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1695
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8059174
telemt_user_connections_current{user="hello"} 1316
telemt_user_octets_from_client{user="hello"} 186055498373 (173.28 GB)
telemt_user_octets_to_client{user="hello"} 3355507960549 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 35639.0 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10566281
telemt_connections_bad_total 646279
telemt_connections_current 2276
telemt_connections_me_current 2276
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 216985
telemt_upstream_connect_attempt_total 42493
telemt_upstream_connect_success_total 40362
telemt_upstream_connect_fail_total 1489
telemt_upstream_connect_attempts_per_request{bucket="1"} 41851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12358
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5924
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1489
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6323
telemt_me_reconnect_success_total 813
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_route_drop_no_conn_total 25109836
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8778073
telemt_me_endpoint_quarantine_total 222
telemt_me_single_endpoint_outage_enter_total 61
telemt_me_single_endpoint_outage_exit_total 61
telemt_me_single_endpoint_outage_reconnect_attempt_total 112
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 112
telemt_me_single_endpoint_shadow_rotate_total 281
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 14026
telemt_desync_full_logged_total 3658
telemt_desync_suppressed_total 10368
telemt_desync_frames_bucket_total{bucket="1_2"} 2584
telemt_desync_frames_bucket_total{bucket="3_10"} 5684
telemt_desync_frames_bucket_total{bucket="gt_10"} 5758
telemt_pool_swap_total 35
telemt_pool_force_close_total 1316
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 10064
telemt_me_writer_removed_unexpected_total 718
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1525
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9215
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1030
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8748
telemt_me_writer_teardown_success_total{mode="normal"} 10740
telemt_me_writer_teardown_noop_total 10070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20810
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.886603
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20810
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 305
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 8799638
telemt_user_connections_current{user="hello"} 2276
telemt_user_octets_from_client{user="hello"} 77954643631 (72.60 GB)
telemt_user_octets_to_client{user="hello"} 415340467977 (386.82 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 165365.6 (45h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10526901
telemt_connections_bad_total 887693
telemt_connections_current 1934
telemt_connections_me_current 1934
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232540
telemt_upstream_connect_attempt_total 100393
telemt_upstream_connect_success_total 99340
telemt_upstream_connect_fail_total 897
telemt_upstream_connect_attempts_per_request{bucket="1"} 100237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 897
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72190
telemt_me_reconnect_success_total 2717
telemt_me_reader_eof_total 2409
telemt_me_idle_close_by_peer_total 2407
telemt_me_route_drop_no_conn_total 5143048
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8307889
telemt_me_endpoint_quarantine_total 1098
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1233
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 44006
telemt_desync_full_logged_total 15020
telemt_desync_suppressed_total 28986
telemt_desync_frames_bucket_total{bucket="1_2"} 8933
telemt_desync_frames_bucket_total{bucket="3_10"} 16908
telemt_desync_frames_bucket_total{bucket="gt_10"} 18165
telemt_pool_swap_total 169
telemt_pool_force_close_total 5032
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 623
telemt_me_draining_writers_reap_progress_total 56250
telemt_me_writer_removed_unexpected_total 2449
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5993
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52730
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4336
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 696
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51218
telemt_me_writer_teardown_success_total{mode="normal"} 58723
telemt_me_writer_teardown_noop_total 56251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114974
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.848393
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114974
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 623
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2275
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8311425
telemt_user_connections_current{user="hello"} 1934
telemt_user_octets_from_client{user="hello"} 188600538097 (175.65 GB)
telemt_user_octets_to_client{user="hello"} 3152253819104 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 730
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 102201.7 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11046620
telemt_connections_bad_total 426559
telemt_connections_current 1727
telemt_connections_me_current 1727
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4584277
telemt_upstream_connect_attempt_total 48542
telemt_upstream_connect_success_total 48181
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 48533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_reconnect_attempts_total 48251
telemt_me_reconnect_success_total 1585
telemt_me_reader_eof_total 1242
telemt_me_idle_close_by_peer_total 1241
telemt_me_route_drop_no_conn_total 3992876
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5310811
telemt_me_endpoint_quarantine_total 663
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 772
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29722
telemt_desync_full_logged_total 10053
telemt_desync_suppressed_total 19669
telemt_desync_frames_bucket_total{bucket="1_2"} 5965
telemt_desync_frames_bucket_total{bucket="3_10"} 11743
telemt_desync_frames_bucket_total{bucket="gt_10"} 12014
telemt_pool_swap_total 108
telemt_pool_force_close_total 3305
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 342
telemt_me_draining_writers_reap_progress_total 35212
telemt_me_writer_removed_unexpected_total 1303
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3141
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33407
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31907
telemt_me_writer_teardown_success_total{mode="normal"} 36548
telemt_me_writer_teardown_noop_total 35219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71767
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.315101
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71767
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 342
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1409
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5303866
telemt_user_connections_current{user="hello"} 1727
telemt_user_octets_from_client{user="hello"} 114132075304 (106.29 GB)
telemt_user_octets_to_client{user="hello"} 2019189728642 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 609
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 83172.4 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1209879
telemt_connections_bad_total 25467
telemt_connections_current 1202
telemt_connections_me_current 1202
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 23694
telemt_upstream_connect_attempt_total 39934
telemt_upstream_connect_success_total 39816
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 39908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 644
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1781
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 739
telemt_me_idle_close_by_peer_total 739
telemt_me_route_drop_no_conn_total 421117
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1072085
telemt_me_endpoint_quarantine_total 704
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 687
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 6190
telemt_desync_full_logged_total 1907
telemt_desync_suppressed_total 4283
telemt_desync_frames_bucket_total{bucket="1_2"} 1409
telemt_desync_frames_bucket_total{bucket="3_10"} 2445
telemt_desync_frames_bucket_total{bucket="gt_10"} 2336
telemt_pool_swap_total 89
telemt_pool_force_close_total 2290
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 33190
telemt_me_writer_removed_unexpected_total 712
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2587
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31344
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2207
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30900
telemt_me_writer_teardown_success_total{mode="normal"} 33931
telemt_me_writer_teardown_noop_total 33194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67125
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.064569
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67125
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 648
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1068365
telemt_user_connections_current{user="hello"} 1202
telemt_user_octets_from_client{user="hello"} 19609500789 (18.26 GB)
telemt_user_octets_to_client{user="hello"} 455947652307 (424.63 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 165370.1 (45h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12826811
telemt_connections_bad_total 1490623
telemt_connections_current 1895
telemt_connections_me_current 1895
telemt_handshake_timeouts_total 361985
telemt_upstream_connect_attempt_total 62248
telemt_upstream_connect_success_total 61927
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 62120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2435
telemt_me_reconnect_success_total 1296
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 4367582
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9707219
telemt_me_endpoint_quarantine_total 1102
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1235
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 39881
telemt_desync_full_logged_total 13014
telemt_desync_suppressed_total 26867
telemt_desync_frames_bucket_total{bucket="1_2"} 9507
telemt_desync_frames_bucket_total{bucket="3_10"} 14728
telemt_desync_frames_bucket_total{bucket="gt_10"} 15646
telemt_pool_swap_total 183
telemt_pool_force_close_total 5048
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 56006
telemt_me_writer_removed_unexpected_total 1211
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4618
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52635
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4874
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50958
telemt_me_writer_teardown_success_total{mode="normal"} 57253
telemt_me_writer_teardown_noop_total 56008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113261
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.090623
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113261
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9675191
telemt_user_connections_current{user="hello"} 1895
telemt_user_octets_from_client{user="hello"} 189407775316 (176.40 GB)
telemt_user_octets_to_client{user="hello"} 4266934789932 (3.88 TB)
telemt_user_unique_ips_current{user="hello"} 650
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 165366.8 (45h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11137689
telemt_connections_bad_total 1256228
telemt_connections_current 1558
telemt_connections_me_current 1558
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 290957
telemt_upstream_connect_attempt_total 88339
telemt_upstream_connect_success_total 87561
telemt_upstream_connect_fail_total 592
telemt_upstream_connect_attempts_per_request{bucket="1"} 88153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 592
telemt_me_reconnect_attempts_total 9516
telemt_me_reconnect_success_total 2227
telemt_me_reader_eof_total 2074
telemt_me_idle_close_by_peer_total 2074
telemt_me_seq_mismatch_total 77
telemt_me_route_drop_no_conn_total 5536036
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8610789
telemt_me_endpoint_quarantine_total 1270
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1235
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 39191
telemt_desync_full_logged_total 12673
telemt_desync_suppressed_total 26518
telemt_desync_frames_bucket_total{bucket="1_2"} 9760
telemt_desync_frames_bucket_total{bucket="3_10"} 14581
telemt_desync_frames_bucket_total{bucket="gt_10"} 14850
telemt_pool_swap_total 174
telemt_pool_force_close_total 4863
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 55617
telemt_me_writer_removed_unexpected_total 2101
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5834
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51956
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50754
telemt_me_writer_teardown_success_total{mode="normal"} 57790
telemt_me_writer_teardown_noop_total 55622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113412
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.015034
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113412
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 376
telemt_me_writer_restored_same_endpoint_total 1805
telemt_me_writer_restored_fallback_total 105
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 8616541
telemt_user_connections_current{user="hello"} 1558
telemt_user_octets_from_client{user="hello"} 151771928345 (141.35 GB)
telemt_user_octets_to_client{user="hello"} 3311017032591 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 250
```