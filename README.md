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

# Server Metrics 2026-03-22 18:42:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 77778.9 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2854233
telemt_connections_bad_total 180266
telemt_connections_current 1399
telemt_connections_me_current 1399
telemt_handshake_timeouts_total 96295
telemt_upstream_connect_attempt_total 28469
telemt_upstream_connect_success_total 28468
telemt_upstream_connect_attempts_per_request{bucket="1"} 28468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18492
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1148
telemt_me_reconnect_success_total 482
telemt_me_reader_eof_total 485
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 2370896
telemt_me_route_drop_channel_closed_total 977
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2418152
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 522
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 605
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
telemt_me_writers_active_current 43
telemt_desync_total 10814
telemt_desync_full_logged_total 3432
telemt_desync_suppressed_total 7382
telemt_desync_frames_bucket_total{bucket="1_2"} 2907
telemt_desync_frames_bucket_total{bucket="3_10"} 4006
telemt_desync_frames_bucket_total{bucket="gt_10"} 3901
telemt_pool_swap_total 86
telemt_pool_force_close_total 2680
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 553
telemt_me_draining_writers_reap_progress_total 26029
telemt_me_writer_removed_unexpected_total 471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1900
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24343
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2627
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23349
telemt_me_writer_teardown_success_total{mode="normal"} 26243
telemt_me_writer_teardown_noop_total 26039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52282
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 271.092998
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52282
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 553
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 427
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2414077
telemt_user_connections_current{user="hello"} 1399
telemt_user_octets_from_client{user="hello"} 35300606412 (32.88 GB)
telemt_user_octets_to_client{user="hello"} 638257864400 (594.42 GB)
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 91145.4 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3760030
telemt_connections_bad_total 338000
telemt_connections_current 637
telemt_connections_me_current 637
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 95693
telemt_upstream_connect_attempt_total 55766
telemt_upstream_connect_success_total 55080
telemt_upstream_connect_fail_total 604
telemt_upstream_connect_attempts_per_request{bucket="1"} 55684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 604
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6377
telemt_me_reconnect_success_total 2336
telemt_me_reader_eof_total 2269
telemt_me_idle_close_by_peer_total 2269
telemt_me_route_drop_no_conn_total 3582419
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2987030
telemt_me_endpoint_quarantine_total 716
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 704
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
telemt_me_writers_active_current 44
telemt_desync_total 11876
telemt_desync_full_logged_total 6637
telemt_desync_suppressed_total 5239
telemt_desync_frames_bucket_total{bucket="1_2"} 2730
telemt_desync_frames_bucket_total{bucket="3_10"} 4648
telemt_desync_frames_bucket_total{bucket="gt_10"} 4498
telemt_pool_swap_total 86
telemt_pool_force_close_total 2600
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 221
telemt_me_draining_writers_reap_progress_total 36253
telemt_me_writer_removed_unexpected_total 2220
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4298
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34186
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33653
telemt_me_writer_teardown_success_total{mode="normal"} 38484
telemt_me_writer_teardown_noop_total 36253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74737
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.420060
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74737
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 221
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 2023
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 2997859
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 38741951715 (36.08 GB)
telemt_user_octets_to_client{user="hello"} 696829571918 (648.97 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 166005.3 (46h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15748510
telemt_connections_bad_total 1510984
telemt_connections_current 2051
telemt_connections_me_current 2051
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 389260
telemt_upstream_connect_attempt_total 74167
telemt_upstream_connect_success_total 74070
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 74087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2760
telemt_me_reconnect_success_total 1415
telemt_me_reader_eof_total 1354
telemt_me_idle_close_by_peer_total 1352
telemt_me_route_drop_no_conn_total 13918206
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12552455
telemt_me_endpoint_quarantine_total 1047
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1237
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 51702
telemt_desync_full_logged_total 16253
telemt_desync_suppressed_total 35449
telemt_desync_frames_bucket_total{bucket="1_2"} 11547
telemt_desync_frames_bucket_total{bucket="3_10"} 20152
telemt_desync_frames_bucket_total{bucket="gt_10"} 20003
telemt_pool_swap_total 179
telemt_pool_force_close_total 6059
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 978
telemt_me_draining_writers_reap_progress_total 54492
telemt_me_writer_removed_unexpected_total 1308
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4779
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50312
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5592
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 467
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48433
telemt_me_writer_teardown_success_total{mode="normal"} 55091
telemt_me_writer_teardown_noop_total 54542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109633
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 306.837130
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109633
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 978
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1219
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12553159
telemt_user_connections_current{user="hello"} 2052
telemt_user_octets_from_client{user="hello"} 182715730825 (170.17 GB)
telemt_user_octets_to_client{user="hello"} 3293077059131 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 746
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 166006.6 (46h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11370528
telemt_connections_bad_total 1122382
telemt_connections_current 1708
telemt_connections_me_current 1708
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 339686
telemt_upstream_connect_attempt_total 86692
telemt_upstream_connect_success_total 85487
telemt_upstream_connect_fail_total 840
telemt_upstream_connect_attempts_per_request{bucket="1"} 86327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3703
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 840
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4099
telemt_me_reconnect_success_total 1694
telemt_me_reader_eof_total 1562
telemt_me_idle_close_by_peer_total 1562
telemt_me_route_drop_no_conn_total 4449659
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8471399
telemt_me_endpoint_quarantine_total 1052
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1257
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 37625
telemt_desync_full_logged_total 12667
telemt_desync_suppressed_total 24958
telemt_desync_frames_bucket_total{bucket="1_2"} 9269
telemt_desync_frames_bucket_total{bucket="3_10"} 14492
telemt_desync_frames_bucket_total{bucket="gt_10"} 13864
telemt_pool_swap_total 176
telemt_pool_force_close_total 5473
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 52980
telemt_me_writer_removed_unexpected_total 1601
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4901
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49524
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47507
telemt_me_writer_teardown_success_total{mode="normal"} 54425
telemt_me_writer_teardown_noop_total 53003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107428
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.062367
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107428
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 8409778
telemt_user_connections_current{user="hello"} 1708
telemt_user_octets_from_client{user="hello"} 210330484441 (195.89 GB)
telemt_user_octets_to_client{user="hello"} 3792903868694 (3.45 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 165970.9 (46h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10698379
telemt_connections_bad_total 921684
telemt_connections_current 1230
telemt_connections_me_current 1230
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342375
telemt_upstream_connect_attempt_total 71816
telemt_upstream_connect_success_total 70767
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 70951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4901
telemt_me_reconnect_success_total 1980
telemt_me_reader_eof_total 1729
telemt_me_idle_close_by_peer_total 1728
telemt_me_route_drop_no_conn_total 5219995
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8081917
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1220
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 37149
telemt_desync_full_logged_total 12288
telemt_desync_suppressed_total 24861
telemt_desync_frames_bucket_total{bucket="1_2"} 9409
telemt_desync_frames_bucket_total{bucket="3_10"} 14225
telemt_desync_frames_bucket_total{bucket="gt_10"} 13515
telemt_pool_swap_total 174
telemt_pool_force_close_total 5405
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 53200
telemt_me_writer_removed_unexpected_total 1870
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5352
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49635
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4860
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47795
telemt_me_writer_teardown_success_total{mode="normal"} 54987
telemt_me_writer_teardown_noop_total 53271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108258
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.637445
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108258
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1706
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 8074404
telemt_user_connections_current{user="hello"} 1230
telemt_user_octets_from_client{user="hello"} 186359639145 (173.56 GB)
telemt_user_octets_to_client{user="hello"} 3361480536385 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 36250.8 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10598453
telemt_connections_bad_total 648708
telemt_connections_current 2196
telemt_connections_me_current 2196
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 219555
telemt_upstream_connect_attempt_total 42726
telemt_upstream_connect_success_total 40584
telemt_upstream_connect_fail_total 1491
telemt_upstream_connect_attempts_per_request{bucket="1"} 42075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5924
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1491
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6347
telemt_me_reconnect_success_total 819
telemt_me_reader_eof_total 523
telemt_me_idle_close_by_peer_total 523
telemt_me_route_drop_no_conn_total 25120489
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8802903
telemt_me_endpoint_quarantine_total 227
telemt_me_single_endpoint_outage_enter_total 61
telemt_me_single_endpoint_outage_exit_total 61
telemt_me_single_endpoint_outage_reconnect_attempt_total 112
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 112
telemt_me_single_endpoint_shadow_rotate_total 285
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
telemt_me_writers_active_current 43
telemt_desync_total 14074
telemt_desync_full_logged_total 3675
telemt_desync_suppressed_total 10399
telemt_desync_frames_bucket_total{bucket="1_2"} 2595
telemt_desync_frames_bucket_total{bucket="3_10"} 5700
telemt_desync_frames_bucket_total{bucket="gt_10"} 5779
telemt_pool_swap_total 36
telemt_pool_force_close_total 1345
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 10263
telemt_me_writer_removed_unexpected_total 724
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1547
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9399
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 289
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8918
telemt_me_writer_teardown_success_total{mode="normal"} 10946
telemt_me_writer_teardown_noop_total 10269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21215
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.467168
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21215
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 306
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8824426
telemt_user_connections_current{user="hello"} 2196
telemt_user_octets_from_client{user="hello"} 78967139463 (73.54 GB)
telemt_user_octets_to_client{user="hello"} 423689715241 (394.59 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 769
telemt_user_unique_ips_recent_window{user="hello"} 316
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 165977.4 (46h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10547486
telemt_connections_bad_total 889006
telemt_connections_current 1420
telemt_connections_me_current 1420
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232691
telemt_upstream_connect_attempt_total 100679
telemt_upstream_connect_success_total 99620
telemt_upstream_connect_fail_total 902
telemt_upstream_connect_attempts_per_request{bucket="1"} 100522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 902
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72201
telemt_me_reconnect_success_total 2727
telemt_me_reader_eof_total 2419
telemt_me_idle_close_by_peer_total 2417
telemt_me_route_drop_no_conn_total 5150017
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8325703
telemt_me_endpoint_quarantine_total 1101
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_me_writers_active_current 48
telemt_desync_total 44175
telemt_desync_full_logged_total 15066
telemt_desync_suppressed_total 29109
telemt_desync_frames_bucket_total{bucket="1_2"} 8967
telemt_desync_frames_bucket_total{bucket="3_10"} 16966
telemt_desync_frames_bucket_total{bucket="gt_10"} 18242
telemt_pool_swap_total 170
telemt_pool_force_close_total 5062
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 626
telemt_me_draining_writers_reap_progress_total 56496
telemt_me_writer_removed_unexpected_total 2459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52957
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4365
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 697
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51434
telemt_me_writer_teardown_success_total{mode="normal"} 58979
telemt_me_writer_teardown_noop_total 56497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115476
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.858584
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115476
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 626
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2285
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8329195
telemt_user_connections_current{user="hello"} 1420
telemt_user_octets_from_client{user="hello"} 189004794533 (176.02 GB)
telemt_user_octets_to_client{user="hello"} 3159135155140 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 102813.8 (28h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11076873
telemt_connections_bad_total 428808
telemt_connections_current 1920
telemt_connections_me_current 1920
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4593197
telemt_upstream_connect_attempt_total 48774
telemt_upstream_connect_success_total 48409
telemt_upstream_connect_fail_total 356
telemt_upstream_connect_attempts_per_request{bucket="1"} 48765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 356
telemt_me_reconnect_attempts_total 48288
telemt_me_reconnect_success_total 1621
telemt_me_reader_eof_total 1280
telemt_me_idle_close_by_peer_total 1279
telemt_me_route_drop_no_conn_total 3998361
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5326544
telemt_me_endpoint_quarantine_total 663
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 774
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
telemt_me_writers_active_current 78
telemt_me_writers_warm_current 6
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29791
telemt_desync_full_logged_total 10078
telemt_desync_suppressed_total 19713
telemt_desync_frames_bucket_total{bucket="1_2"} 5978
telemt_desync_frames_bucket_total{bucket="3_10"} 11768
telemt_desync_frames_bucket_total{bucket="gt_10"} 12045
telemt_pool_swap_total 108
telemt_pool_force_close_total 3305
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 342
telemt_me_draining_writers_reap_progress_total 35356
telemt_me_writer_removed_unexpected_total 1341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3183
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33547
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32051
telemt_me_writer_teardown_success_total{mode="normal"} 36730
telemt_me_writer_teardown_noop_total 35363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.316408
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 342
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1445
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5319609
telemt_user_connections_current{user="hello"} 1920
telemt_user_octets_from_client{user="hello"} 114458113328 (106.60 GB)
telemt_user_octets_to_client{user="hello"} 2027362411466 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 731
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 83784.2 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1225592
telemt_connections_bad_total 26842
telemt_connections_current 1286
telemt_connections_me_current 1286
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 23822
telemt_upstream_connect_attempt_total 40162
telemt_upstream_connect_success_total 40041
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 40135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 652
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1785
telemt_me_reconnect_success_total 770
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 742
telemt_me_route_drop_no_conn_total 426226
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1085232
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
telemt_me_writers_warm_current 34
telemt_desync_total 6296
telemt_desync_full_logged_total 1941
telemt_desync_suppressed_total 4355
telemt_desync_frames_bucket_total{bucket="1_2"} 1432
telemt_desync_frames_bucket_total{bucket="3_10"} 2486
telemt_desync_frames_bucket_total{bucket="gt_10"} 2378
telemt_pool_swap_total 89
telemt_pool_force_close_total 2290
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 33351
telemt_me_writer_removed_unexpected_total 716
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31498
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2207
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31061
telemt_me_writer_teardown_success_total{mode="normal"} 34096
telemt_me_writer_teardown_noop_total 33355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67451
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.069210
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67451
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 652
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1081508
telemt_user_connections_current{user="hello"} 1286
telemt_user_octets_from_client{user="hello"} 19823987517 (18.46 GB)
telemt_user_octets_to_client{user="hello"} 460930030919 (429.27 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 165981.9 (46h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12850541
telemt_connections_bad_total 1493681
telemt_connections_current 1833
telemt_connections_me_current 1833
telemt_handshake_timeouts_total 363246
telemt_upstream_connect_attempt_total 62504
telemt_upstream_connect_success_total 62177
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 62370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2435
telemt_me_reconnect_success_total 1296
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 4377742
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9725925
telemt_me_endpoint_quarantine_total 1109
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1242
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 39985
telemt_desync_full_logged_total 13045
telemt_desync_suppressed_total 26940
telemt_desync_frames_bucket_total{bucket="1_2"} 9539
telemt_desync_frames_bucket_total{bucket="3_10"} 14766
telemt_desync_frames_bucket_total{bucket="gt_10"} 15680
telemt_pool_swap_total 184
telemt_pool_force_close_total 5073
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 642
telemt_me_draining_writers_reap_progress_total 56251
telemt_me_writer_removed_unexpected_total 1211
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4633
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52865
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4899
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51178
telemt_me_writer_teardown_success_total{mode="normal"} 57498
telemt_me_writer_teardown_noop_total 56253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113751
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.098550
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113751
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 642
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9693860
telemt_user_connections_current{user="hello"} 1833
telemt_user_octets_from_client{user="hello"} 189789663916 (176.76 GB)
telemt_user_octets_to_client{user="hello"} 4274223015664 (3.89 TB)
telemt_user_unique_ips_current{user="hello"} 617
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 165978.6 (46h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11160855
telemt_connections_bad_total 1258792
telemt_connections_current 1680
telemt_connections_me_current 1680
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 292002
telemt_upstream_connect_attempt_total 88670
telemt_upstream_connect_success_total 87871
telemt_upstream_connect_fail_total 602
telemt_upstream_connect_attempts_per_request{bucket="1"} 88473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2062
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 602
telemt_me_reconnect_attempts_total 9566
telemt_me_reconnect_success_total 2275
telemt_me_reader_eof_total 2121
telemt_me_idle_close_by_peer_total 2120
telemt_me_seq_mismatch_total 77
telemt_me_route_drop_no_conn_total 5551551
telemt_me_route_drop_channel_closed_total 352
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8629327
telemt_me_endpoint_quarantine_total 1272
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1240
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
telemt_me_writers_active_current 84
telemt_desync_total 39264
telemt_desync_full_logged_total 12700
telemt_desync_suppressed_total 26564
telemt_desync_frames_bucket_total{bucket="1_2"} 9771
telemt_desync_frames_bucket_total{bucket="3_10"} 14604
telemt_desync_frames_bucket_total{bucket="gt_10"} 14889
telemt_pool_swap_total 174
telemt_pool_force_close_total 4863
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 629
telemt_me_draining_writers_reap_progress_total 55825
telemt_me_writer_removed_unexpected_total 2152
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5904
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52146
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50962
telemt_me_writer_teardown_success_total{mode="normal"} 58050
telemt_me_writer_teardown_noop_total 55830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113880
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.038408
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113880
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 629
telemt_me_refill_failed_total 376
telemt_me_writer_restored_same_endpoint_total 1853
telemt_me_writer_restored_fallback_total 105
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8635070
telemt_user_connections_current{user="hello"} 1680
telemt_user_octets_from_client{user="hello"} 152031415381 (141.59 GB)
telemt_user_octets_to_client{user="hello"} 3320234296067 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 199
```