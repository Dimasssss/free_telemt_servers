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

# Server Metrics 2026-03-22 20:20:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 83628.8 (23h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3103456
telemt_connections_bad_total 213851
telemt_connections_current 1141
telemt_connections_me_current 1141
telemt_handshake_timeouts_total 99140
telemt_upstream_connect_attempt_total 30628
telemt_upstream_connect_success_total 30627
telemt_upstream_connect_attempts_per_request{bucket="1"} 30627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1220
telemt_me_reconnect_success_total 517
telemt_me_reader_eof_total 524
telemt_me_idle_close_by_peer_total 524
telemt_me_route_drop_no_conn_total 2788729
telemt_me_route_drop_channel_closed_total 1108
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2625026
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 563
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 646
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 11230
telemt_desync_full_logged_total 3555
telemt_desync_suppressed_total 7675
telemt_desync_frames_bucket_total{bucket="1_2"} 3005
telemt_desync_frames_bucket_total{bucket="3_10"} 4155
telemt_desync_frames_bucket_total{bucket="gt_10"} 4070
telemt_pool_swap_total 92
telemt_pool_force_close_total 2877
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 591
telemt_me_draining_writers_reap_progress_total 28018
telemt_me_writer_removed_unexpected_total 508
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2036
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26194
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25141
telemt_me_writer_teardown_success_total{mode="normal"} 28230
telemt_me_writer_teardown_noop_total 28029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56259
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 321.165440
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56259
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 591
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 2616614
telemt_user_connections_current{user="hello"} 1141
telemt_user_octets_from_client{user="hello"} 38423144508 (35.78 GB)
telemt_user_octets_to_client{user="hello"} 690463148728 (643.04 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 96994.8 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3850695
telemt_connections_bad_total 340767
telemt_connections_current 890
telemt_connections_me_current 890
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98216
telemt_upstream_connect_attempt_total 58725
telemt_upstream_connect_success_total 58007
telemt_upstream_connect_fail_total 634
telemt_upstream_connect_attempts_per_request{bucket="1"} 58641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 634
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6819
telemt_me_reconnect_success_total 2659
telemt_me_reader_eof_total 2610
telemt_me_idle_close_by_peer_total 2610
telemt_me_route_drop_no_conn_total 3611120
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3067751
telemt_me_endpoint_quarantine_total 739
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 745
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 12305
telemt_desync_full_logged_total 6880
telemt_desync_suppressed_total 5425
telemt_desync_frames_bucket_total{bucket="1_2"} 2811
telemt_desync_frames_bucket_total{bucket="3_10"} 4822
telemt_desync_frames_bucket_total{bucket="gt_10"} 4672
telemt_pool_swap_total 90
telemt_pool_force_close_total 2746
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 38640
telemt_me_writer_removed_unexpected_total 2554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36458
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2321
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35894
telemt_me_writer_teardown_success_total{mode="normal"} 41213
telemt_me_writer_teardown_noop_total 38641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79854
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.255484
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79854
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2346
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 3078506
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 40435971471 (37.66 GB)
telemt_user_octets_to_client{user="hello"} 738302347686 (687.60 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 171854.8 (47h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15984970
telemt_connections_bad_total 1549412
telemt_connections_current 1923
telemt_connections_me_current 1923
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 393110
telemt_upstream_connect_attempt_total 76280
telemt_upstream_connect_success_total 76182
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 76199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1689
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2810
telemt_me_reconnect_success_total 1447
telemt_me_reader_eof_total 1390
telemt_me_idle_close_by_peer_total 1388
telemt_me_route_drop_no_conn_total 13985470
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12737740
telemt_me_endpoint_quarantine_total 1085
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1279
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 43
telemt_desync_total 52596
telemt_desync_full_logged_total 16562
telemt_desync_suppressed_total 36034
telemt_desync_frames_bucket_total{bucket="1_2"} 11719
telemt_desync_frames_bucket_total{bucket="3_10"} 20481
telemt_desync_frames_bucket_total{bucket="gt_10"} 20396
telemt_pool_swap_total 185
telemt_pool_force_close_total 6251
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1018
telemt_me_draining_writers_reap_progress_total 56420
telemt_me_writer_removed_unexpected_total 1342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4936
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52103
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5781
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50169
telemt_me_writer_teardown_success_total{mode="normal"} 57039
telemt_me_writer_teardown_noop_total 56471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113510
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.726673
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113510
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1018
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1249
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 12738200
telemt_user_connections_current{user="hello"} 1923
telemt_user_octets_from_client{user="hello"} 186438375769 (173.63 GB)
telemt_user_octets_to_client{user="hello"} 3395008827615 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 826
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 171856.9 (47h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11565313
telemt_connections_bad_total 1158797
telemt_connections_current 1353
telemt_connections_me_current 1353
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343074
telemt_upstream_connect_attempt_total 88819
telemt_upstream_connect_success_total 87551
telemt_upstream_connect_fail_total 850
telemt_upstream_connect_attempts_per_request{bucket="1"} 88401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 850
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4159
telemt_me_reconnect_success_total 1739
telemt_me_reader_eof_total 1605
telemt_me_idle_close_by_peer_total 1605
telemt_me_route_drop_no_conn_total 4505062
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8617071
telemt_me_endpoint_quarantine_total 1084
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1300
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
telemt_me_writers_active_current 44
telemt_desync_total 38205
telemt_desync_full_logged_total 12854
telemt_desync_suppressed_total 25351
telemt_desync_frames_bucket_total{bucket="1_2"} 9421
telemt_desync_frames_bucket_total{bucket="3_10"} 14701
telemt_desync_frames_bucket_total{bucket="gt_10"} 14083
telemt_pool_swap_total 182
telemt_pool_force_close_total 5636
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 54835
telemt_me_writer_removed_unexpected_total 1643
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5064
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51261
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 506
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49199
telemt_me_writer_teardown_success_total{mode="normal"} 56325
telemt_me_writer_teardown_noop_total 54860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111185
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.713114
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111185
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1485
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8555184
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 215258437833 (200.48 GB)
telemt_user_octets_to_client{user="hello"} 3866020275394 (3.52 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 171824.8 (47h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10845675
telemt_connections_bad_total 938759
telemt_connections_current 1106
telemt_connections_me_current 1106
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344075
telemt_upstream_connect_attempt_total 73964
telemt_upstream_connect_success_total 72787
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 72974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 1386
telemt_me_reconnect_attempts_total 5024
telemt_me_reconnect_success_total 2032
telemt_me_reader_eof_total 1775
telemt_me_idle_close_by_peer_total 1774
telemt_me_route_drop_no_conn_total 5271303
telemt_me_route_drop_channel_closed_total 375
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8203778
telemt_me_endpoint_quarantine_total 1163
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1259
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_me_writers_active_current 47
telemt_desync_total 37564
telemt_desync_full_logged_total 12436
telemt_desync_suppressed_total 25128
telemt_desync_frames_bucket_total{bucket="1_2"} 9498
telemt_desync_frames_bucket_total{bucket="3_10"} 14360
telemt_desync_frames_bucket_total{bucket="gt_10"} 13706
telemt_pool_swap_total 180
telemt_pool_force_close_total 5581
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 714
telemt_me_draining_writers_reap_progress_total 54929
telemt_me_writer_removed_unexpected_total 1919
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5530
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51237
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5030
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49348
telemt_me_writer_teardown_success_total{mode="normal"} 56767
telemt_me_writer_teardown_noop_total 55000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111767
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.001123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111767
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 714
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 1750
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8196026
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 191144940797 (178.02 GB)
telemt_user_octets_to_client{user="hello"} 3412055308709 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 42100.6 (11h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10857763
telemt_connections_bad_total 659415
telemt_connections_current 1759
telemt_connections_me_current 1759
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 235803
telemt_upstream_connect_attempt_total 45655
telemt_upstream_connect_success_total 43379
telemt_upstream_connect_fail_total 1559
telemt_upstream_connect_attempts_per_request{bucket="1"} 44938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5963
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1559
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6578
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 25210165
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9018777
telemt_me_endpoint_quarantine_total 275
telemt_me_single_endpoint_outage_enter_total 66
telemt_me_single_endpoint_outage_exit_total 66
telemt_me_single_endpoint_outage_reconnect_attempt_total 118
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 118
telemt_me_single_endpoint_shadow_rotate_total 328
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 14735
telemt_desync_full_logged_total 3888
telemt_desync_suppressed_total 10847
telemt_desync_frames_bucket_total{bucket="1_2"} 2743
telemt_desync_frames_bucket_total{bucket="3_10"} 5986
telemt_desync_frames_bucket_total{bucket="gt_10"} 6006
telemt_pool_swap_total 42
telemt_pool_force_close_total 1536
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 436
telemt_me_draining_writers_reap_progress_total 12047
telemt_me_writer_removed_unexpected_total 823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1787
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11033
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10511
telemt_me_writer_teardown_success_total{mode="normal"} 12820
telemt_me_writer_teardown_noop_total 12066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24886
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.961711
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24886
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 436
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 622
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 9040859
telemt_user_connections_current{user="hello"} 1759
telemt_user_octets_from_client{user="hello"} 82736367551 (77.05 GB)
telemt_user_octets_to_client{user="hello"} 505095053047 (470.41 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 686
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 171826.9 (47h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10734279
telemt_connections_bad_total 907770
telemt_connections_current 1541
telemt_connections_me_current 1541
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 236290
telemt_upstream_connect_attempt_total 103398
telemt_upstream_connect_success_total 102310
telemt_upstream_connect_fail_total 929
telemt_upstream_connect_attempts_per_request{bucket="1"} 103239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38542
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1340
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 929
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72391
telemt_me_reconnect_success_total 2831
telemt_me_reader_eof_total 2521
telemt_me_idle_close_by_peer_total 2519
telemt_me_route_drop_no_conn_total 5205117
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8478171
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1283
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 45141
telemt_desync_full_logged_total 15376
telemt_desync_suppressed_total 29765
telemt_desync_frames_bucket_total{bucket="1_2"} 9146
telemt_desync_frames_bucket_total{bucket="3_10"} 17294
telemt_desync_frames_bucket_total{bucket="gt_10"} 18701
telemt_pool_swap_total 175
telemt_pool_force_close_total 5229
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 641
telemt_me_draining_writers_reap_progress_total 58903
telemt_me_writer_removed_unexpected_total 2559
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6249
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55239
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4502
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 727
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53674
telemt_me_writer_teardown_success_total{mode="normal"} 61488
telemt_me_writer_teardown_noop_total 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120392
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.054088
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120392
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 641
telemt_me_refill_failed_total 4285
telemt_me_writer_restored_same_endpoint_total 2380
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 8481424
telemt_user_connections_current{user="hello"} 1541
telemt_user_octets_from_client{user="hello"} 191988866289 (178.80 GB)
telemt_user_octets_to_client{user="hello"} 3225851487060 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 108663.0 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11328060
telemt_connections_bad_total 454703
telemt_connections_current 1207
telemt_connections_me_current 1207
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4656182
telemt_upstream_connect_attempt_total 51483
telemt_upstream_connect_success_total 51100
telemt_upstream_connect_fail_total 374
telemt_upstream_connect_attempts_per_request{bucket="1"} 51474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 374
telemt_me_reconnect_attempts_total 48550
telemt_me_reconnect_success_total 1678
telemt_me_reader_eof_total 1336
telemt_me_idle_close_by_peer_total 1335
telemt_me_route_drop_no_conn_total 4042577
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5457483
telemt_me_endpoint_quarantine_total 702
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 820
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30695
telemt_desync_full_logged_total 10398
telemt_desync_suppressed_total 20297
telemt_desync_frames_bucket_total{bucket="1_2"} 6114
telemt_desync_frames_bucket_total{bucket="3_10"} 12147
telemt_desync_frames_bucket_total{bucket="gt_10"} 12434
telemt_pool_swap_total 114
telemt_pool_force_close_total 3485
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 37846
telemt_me_writer_removed_unexpected_total 1396
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3342
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35934
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3044
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34361
telemt_me_writer_teardown_success_total{mode="normal"} 39276
telemt_me_writer_teardown_noop_total 37853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77129
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.479857
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77129
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 2724
telemt_me_writer_restored_same_endpoint_total 1492
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5450305
telemt_user_connections_current{user="hello"} 1207
telemt_user_octets_from_client{user="hello"} 117318025096 (109.26 GB)
telemt_user_octets_to_client{user="hello"} 2088830714774 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 89634.8 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1352641
telemt_connections_bad_total 30787
telemt_connections_current 978
telemt_connections_me_current 978
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25280
telemt_upstream_connect_attempt_total 42362
telemt_upstream_connect_success_total 42232
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 42335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 726
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1995
telemt_me_reconnect_success_total 817
telemt_me_reader_eof_total 795
telemt_me_idle_close_by_peer_total 795
telemt_me_route_drop_no_conn_total 473447
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1200939
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 739
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
telemt_me_writers_active_current 45
telemt_desync_total 7224
telemt_desync_full_logged_total 2243
telemt_desync_suppressed_total 4981
telemt_desync_frames_bucket_total{bucket="1_2"} 1584
telemt_desync_frames_bucket_total{bucket="3_10"} 2838
telemt_desync_frames_bucket_total{bucket="gt_10"} 2802
telemt_pool_swap_total 96
telemt_pool_force_close_total 2492
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 144
telemt_me_draining_writers_reap_progress_total 35300
telemt_me_writer_removed_unexpected_total 767
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2787
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33311
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2405
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32808
telemt_me_writer_teardown_success_total{mode="normal"} 36098
telemt_me_writer_teardown_noop_total 35304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71402
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.531514
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71402
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 144
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 691
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1197005
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 22999671745 (21.42 GB)
telemt_user_octets_to_client{user="hello"} 506222909059 (471.46 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 171831.4 (47h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13051347
telemt_connections_bad_total 1527761
telemt_connections_current 1440
telemt_connections_me_current 1440
telemt_handshake_timeouts_total 373979
telemt_upstream_connect_attempt_total 64936
telemt_upstream_connect_success_total 64604
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 64801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2542
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 1300
telemt_me_idle_close_by_peer_total 1300
telemt_me_route_drop_no_conn_total 4424945
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9874706
telemt_me_endpoint_quarantine_total 1151
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1284
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
telemt_desync_total 40923
telemt_desync_full_logged_total 13344
telemt_desync_suppressed_total 27579
telemt_desync_frames_bucket_total{bucket="1_2"} 9777
telemt_desync_frames_bucket_total{bucket="3_10"} 15091
telemt_desync_frames_bucket_total{bucket="gt_10"} 16055
telemt_pool_swap_total 190
telemt_pool_force_close_total 5225
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 58497
telemt_me_writer_removed_unexpected_total 1251
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4775
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55012
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5051
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53272
telemt_me_writer_teardown_success_total{mode="normal"} 59787
telemt_me_writer_teardown_noop_total 58499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118286
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.464559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118286
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1167
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 9842366
telemt_user_connections_current{user="hello"} 1440
telemt_user_octets_from_client{user="hello"} 192263834744 (179.06 GB)
telemt_user_octets_to_client{user="hello"} 4349438725200 (3.96 TB)
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 171828.0 (47h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11349445
telemt_connections_bad_total 1284109
telemt_connections_current 1219
telemt_connections_me_current 1219
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 298916
telemt_upstream_connect_attempt_total 91381
telemt_upstream_connect_success_total 90557
telemt_upstream_connect_fail_total 617
telemt_upstream_connect_attempts_per_request{bucket="1"} 91174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 617
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9810
telemt_me_reconnect_success_total 2352
telemt_me_reader_eof_total 2199
telemt_me_idle_close_by_peer_total 2198
telemt_me_seq_mismatch_total 79
telemt_me_route_drop_no_conn_total 5599819
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8776686
telemt_me_endpoint_quarantine_total 1308
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1284
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
telemt_me_writers_active_current 45
telemt_desync_total 40111
telemt_desync_full_logged_total 12960
telemt_desync_suppressed_total 27151
telemt_desync_frames_bucket_total{bucket="1_2"} 10007
telemt_desync_frames_bucket_total{bucket="3_10"} 14899
telemt_desync_frames_bucket_total{bucket="gt_10"} 15205
telemt_pool_swap_total 180
telemt_pool_force_close_total 5023
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 58300
telemt_me_writer_removed_unexpected_total 2231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6110
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54497
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4552
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53277
telemt_me_writer_teardown_success_total{mode="normal"} 60607
telemt_me_writer_teardown_noop_total 58305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118912
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.179838
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118912
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 385
telemt_me_writer_restored_same_endpoint_total 1918
telemt_me_writer_restored_fallback_total 109
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 8782233
telemt_user_connections_current{user="hello"} 1219
telemt_user_octets_from_client{user="hello"} 155469731569 (144.79 GB)
telemt_user_octets_to_client{user="hello"} 3399995790271 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 164
```