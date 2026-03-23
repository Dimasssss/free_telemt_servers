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

# Server Metrics 2026-03-23 05:56:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 118214.4 (32h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4210031
telemt_connections_bad_total 400332
telemt_connections_current 1446
telemt_connections_me_current 1446
telemt_handshake_timeouts_total 141400
telemt_upstream_connect_attempt_total 43976
telemt_upstream_connect_success_total 43975
telemt_upstream_connect_attempts_per_request{bucket="1"} 43975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 97
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1544
telemt_me_reconnect_success_total 689
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 3447627
telemt_me_route_drop_channel_closed_total 1345
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3445748
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 841
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 926
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 14265
telemt_desync_full_logged_total 4522
telemt_desync_suppressed_total 9743
telemt_desync_frames_bucket_total{bucket="1_2"} 3678
telemt_desync_frames_bucket_total{bucket="3_10"} 5328
telemt_desync_frames_bucket_total{bucket="gt_10"} 5259
telemt_pool_swap_total 131
telemt_pool_force_close_total 4009
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 760
telemt_me_draining_writers_reap_progress_total 40291
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2896
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37680
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36282
telemt_me_writer_teardown_success_total{mode="normal"} 40576
telemt_me_writer_teardown_noop_total 40304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80880
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 439.003686
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80880
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 760
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 618
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 3433064
telemt_user_connections_current{user="hello"} 1446
telemt_user_octets_from_client{user="hello"} 45900283420 (42.75 GB)
telemt_user_octets_to_client{user="hello"} 901202023608 (839.31 GB)
telemt_user_unique_ips_current{user="hello"} 603
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 131580.5 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4177202
telemt_connections_bad_total 387687
telemt_connections_current 646
telemt_connections_me_current 646
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 109336
telemt_upstream_connect_attempt_total 82060
telemt_upstream_connect_success_total 81076
telemt_upstream_connect_fail_total 872
telemt_upstream_connect_attempts_per_request{bucket="1"} 81948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 872
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11019
telemt_me_reconnect_success_total 3965
telemt_me_reader_eof_total 3936
telemt_me_idle_close_by_peer_total 3935
telemt_me_route_drop_no_conn_total 3677185
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3312848
telemt_me_endpoint_quarantine_total 1074
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1038
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
telemt_desync_total 13617
telemt_desync_full_logged_total 7684
telemt_desync_suppressed_total 5933
telemt_desync_frames_bucket_total{bucket="1_2"} 3095
telemt_desync_frames_bucket_total{bucket="3_10"} 5339
telemt_desync_frames_bucket_total{bucket="gt_10"} 5183
telemt_pool_swap_total 124
telemt_pool_force_close_total 3441
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 270
telemt_me_draining_writers_reap_progress_total 55360
telemt_me_writer_removed_unexpected_total 3858
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6984
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52277
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2932
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51919
telemt_me_writer_teardown_success_total{mode="normal"} 59261
telemt_me_writer_teardown_noop_total 55361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114622
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.992123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114622
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 270
telemt_me_refill_failed_total 279
telemt_me_writer_restored_same_endpoint_total 3512
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 3327263
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 44760445915 (41.69 GB)
telemt_user_octets_to_client{user="hello"} 841168425953 (783.40 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 206440.3 (57h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16725107
telemt_connections_bad_total 1693891
telemt_connections_current 1719
telemt_connections_me_current 1719
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 410661
telemt_upstream_connect_attempt_total 92651
telemt_upstream_connect_success_total 92540
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 92557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1733
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3272
telemt_me_reconnect_success_total 1700
telemt_me_reader_eof_total 1658
telemt_me_idle_close_by_peer_total 1655
telemt_me_route_drop_no_conn_total 14130902
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13287583
telemt_me_endpoint_quarantine_total 1405
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1565
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 55497
telemt_desync_full_logged_total 17734
telemt_desync_suppressed_total 37763
telemt_desync_frames_bucket_total{bucket="1_2"} 12365
telemt_desync_frames_bucket_total{bucket="3_10"} 21747
telemt_desync_frames_bucket_total{bucket="gt_10"} 21385
telemt_pool_swap_total 224
telemt_pool_force_close_total 7175
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1108
telemt_me_draining_writers_reap_progress_total 71396
telemt_me_writer_removed_unexpected_total 1591
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5985
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66288
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6705
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64221
telemt_me_writer_teardown_success_total{mode="normal"} 72273
telemt_me_writer_teardown_noop_total 71450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143723
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.350303
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143723
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1108
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1471
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13287364
telemt_user_connections_current{user="hello"} 1719
telemt_user_octets_from_client{user="hello"} 201088183489 (187.28 GB)
telemt_user_octets_to_client{user="hello"} 3614551114803 (3.29 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 206441.6 (57h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12218272
telemt_connections_bad_total 1297788
telemt_connections_current 1180
telemt_connections_me_current 1180
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 354420
telemt_upstream_connect_attempt_total 107131
telemt_upstream_connect_success_total 105716
telemt_upstream_connect_fail_total 901
telemt_upstream_connect_attempts_per_request{bucket="1"} 106617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 901
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4747
telemt_me_reconnect_success_total 2044
telemt_me_reader_eof_total 1903
telemt_me_idle_close_by_peer_total 1903
telemt_me_route_drop_no_conn_total 4619696
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9034812
telemt_me_endpoint_quarantine_total 1411
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1580
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
telemt_me_writers_active_current 44
telemt_desync_total 39735
telemt_desync_full_logged_total 13428
telemt_desync_suppressed_total 26307
telemt_desync_frames_bucket_total{bucket="1_2"} 9855
telemt_desync_frames_bucket_total{bucket="3_10"} 15255
telemt_desync_frames_bucket_total{bucket="gt_10"} 14625
telemt_pool_swap_total 221
telemt_pool_force_close_total 6523
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 69563
telemt_me_writer_removed_unexpected_total 1933
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6097
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65262
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6010
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 513
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63040
telemt_me_writer_teardown_success_total{mode="normal"} 71359
telemt_me_writer_teardown_noop_total 69588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140947
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.727407
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140947
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1744
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8972333
telemt_user_connections_current{user="hello"} 1180
telemt_user_octets_from_client{user="hello"} 220723644992 (205.56 GB)
telemt_user_octets_to_client{user="hello"} 4040876928079 (3.68 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 206405.8 (57h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11365615
telemt_connections_bad_total 1044318
telemt_connections_current 1115
telemt_connections_me_current 1115
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 360547
telemt_upstream_connect_attempt_total 91504
telemt_upstream_connect_success_total 89925
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 90130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5919
telemt_me_reconnect_success_total 2499
telemt_me_reader_eof_total 2241
telemt_me_idle_close_by_peer_total 2240
telemt_me_route_drop_no_conn_total 5388907
telemt_me_route_drop_channel_closed_total 386
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8542595
telemt_me_endpoint_quarantine_total 1462
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1545
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_desync_total 38884
telemt_desync_full_logged_total 12912
telemt_desync_suppressed_total 25972
telemt_desync_frames_bucket_total{bucket="1_2"} 9814
telemt_desync_frames_bucket_total{bucket="3_10"} 14887
telemt_desync_frames_bucket_total{bucket="gt_10"} 14183
telemt_pool_swap_total 217
telemt_pool_force_close_total 6412
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 764
telemt_me_draining_writers_reap_progress_total 70155
telemt_me_writer_removed_unexpected_total 2386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6837
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65641
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5838
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 574
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63743
telemt_me_writer_teardown_success_total{mode="normal"} 72478
telemt_me_writer_teardown_noop_total 70226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142704
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.291408
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142704
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 764
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2175
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8534345
telemt_user_connections_current{user="hello"} 1115
telemt_user_octets_from_client{user="hello"} 194480247387 (181.12 GB)
telemt_user_octets_to_client{user="hello"} 3539850425149 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 76685.9 (21h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11755564
telemt_connections_bad_total 712694
telemt_connections_current 2044
telemt_connections_me_current 2044
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 324396
telemt_upstream_connect_attempt_total 68170
telemt_upstream_connect_success_total 64568
telemt_upstream_connect_fail_total 2323
telemt_upstream_connect_attempts_per_request{bucket="1"} 66891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2323
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8528
telemt_me_reconnect_success_total 1584
telemt_me_reader_eof_total 1005
telemt_me_idle_close_by_peer_total 1004
telemt_me_route_drop_no_conn_total 25399221
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9708983
telemt_me_endpoint_quarantine_total 612
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 617
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 17454
telemt_desync_full_logged_total 4897
telemt_desync_suppressed_total 12557
telemt_desync_frames_bucket_total{bucket="1_2"} 3376
telemt_desync_frames_bucket_total{bucket="3_10"} 7149
telemt_desync_frames_bucket_total{bucket="gt_10"} 6929
telemt_pool_swap_total 79
telemt_pool_force_close_total 2443
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 533
telemt_me_draining_writers_reap_progress_total 25448
telemt_me_writer_removed_unexpected_total 1462
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3282
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23580
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23005
telemt_me_writer_teardown_success_total{mode="normal"} 26862
telemt_me_writer_teardown_noop_total 25467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52329
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.159161
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52329
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 533
telemt_me_refill_failed_total 353
telemt_me_writer_restored_same_endpoint_total 1014
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 9736491
telemt_user_connections_current{user="hello"} 2044
telemt_user_octets_from_client{user="hello"} 91520428075 (85.24 GB)
telemt_user_octets_to_client{user="hello"} 748126331277 (696.75 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 764
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 206412.5 (57h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11341878
telemt_connections_bad_total 997330
telemt_connections_current 1383
telemt_connections_me_current 1383
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 257263
telemt_upstream_connect_attempt_total 120564
telemt_upstream_connect_success_total 119280
telemt_upstream_connect_fail_total 1107
telemt_upstream_connect_attempts_per_request{bucket="1"} 120387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1107
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73705
telemt_me_reconnect_success_total 3308
telemt_me_reader_eof_total 2983
telemt_me_idle_close_by_peer_total 2980
telemt_me_route_drop_no_conn_total 5334690
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8927960
telemt_me_endpoint_quarantine_total 1417
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1572
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
telemt_desync_total 47502
telemt_desync_full_logged_total 16347
telemt_desync_suppressed_total 31155
telemt_desync_frames_bucket_total{bucket="1_2"} 9664
telemt_desync_frames_bucket_total{bucket="3_10"} 18212
telemt_desync_frames_bucket_total{bucket="gt_10"} 19626
telemt_pool_swap_total 213
telemt_pool_force_close_total 6123
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 74314
telemt_me_writer_removed_unexpected_total 3000
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7389
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69972
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5373
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 750
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68191
telemt_me_writer_teardown_success_total{mode="normal"} 77361
telemt_me_writer_teardown_noop_total 74315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151676
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.392967
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151676
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2776
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8930507
telemt_user_connections_current{user="hello"} 1383
telemt_user_octets_from_client{user="hello"} 199611054825 (185.90 GB)
telemt_user_octets_to_client{user="hello"} 3418805581952 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 143248.7 (39h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12139629
telemt_connections_bad_total 495133
telemt_connections_current 1271
telemt_connections_me_current 1271
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4897779
telemt_upstream_connect_attempt_total 69464
telemt_upstream_connect_success_total 68972
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 69451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_reconnect_attempts_total 49412
telemt_me_reconnect_success_total 1980
telemt_me_reader_eof_total 1666
telemt_me_idle_close_by_peer_total 1665
telemt_me_route_drop_no_conn_total 4154754
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5833334
telemt_me_endpoint_quarantine_total 988
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1104
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32828
telemt_desync_full_logged_total 11250
telemt_desync_suppressed_total 21578
telemt_desync_frames_bucket_total{bucket="1_2"} 6602
telemt_desync_frames_bucket_total{bucket="3_10"} 12923
telemt_desync_frames_bucket_total{bucket="gt_10"} 13303
telemt_pool_swap_total 153
telemt_pool_force_close_total 4289
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 54178
telemt_me_writer_removed_unexpected_total 1703
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51656
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3845
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49889
telemt_me_writer_teardown_success_total{mode="normal"} 55939
telemt_me_writer_teardown_noop_total 54185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.876448
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 2755
telemt_me_writer_restored_same_endpoint_total 1749
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5825200
telemt_user_connections_current{user="hello"} 1271
telemt_user_octets_from_client{user="hello"} 122162879588 (113.77 GB)
telemt_user_octets_to_client{user="hello"} 2270926261586 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 124219.5 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1730126
telemt_connections_bad_total 37689
telemt_connections_current 865
telemt_connections_me_current 865
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 38068
telemt_upstream_connect_attempt_total 58339
telemt_upstream_connect_success_total 58144
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 58301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 855
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2522
telemt_me_reconnect_success_total 1028
telemt_me_reader_eof_total 1024
telemt_me_idle_close_by_peer_total 1024
telemt_me_route_drop_no_conn_total 585217
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1536421
telemt_me_endpoint_quarantine_total 1056
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1024
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
telemt_me_writers_active_current 43
telemt_desync_total 10549
telemt_desync_full_logged_total 2976
telemt_desync_suppressed_total 7573
telemt_desync_frames_bucket_total{bucket="1_2"} 3340
telemt_desync_frames_bucket_total{bucket="3_10"} 3948
telemt_desync_frames_bucket_total{bucket="gt_10"} 3261
telemt_pool_swap_total 134
telemt_pool_force_close_total 3387
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 49764
telemt_me_writer_removed_unexpected_total 986
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3753
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47045
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3299
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46377
telemt_me_writer_teardown_success_total{mode="normal"} 50798
telemt_me_writer_teardown_noop_total 49768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100566
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.723529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100566
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1531965
telemt_user_connections_current{user="hello"} 865
telemt_user_octets_from_client{user="hello"} 27885666037 (25.97 GB)
telemt_user_octets_to_client{user="hello"} 621787805719 (579.09 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 206417.0 (57h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13621772
telemt_connections_bad_total 1647574
telemt_connections_current 1331
telemt_connections_me_current 1331
telemt_handshake_timeouts_total 399889
telemt_upstream_connect_attempt_total 83299
telemt_upstream_connect_success_total 82930
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 83162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3290
telemt_me_reconnect_success_total 1636
telemt_me_reader_eof_total 1629
telemt_me_idle_close_by_peer_total 1629
telemt_me_route_drop_no_conn_total 4541120
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10272177
telemt_me_endpoint_quarantine_total 1534
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1571
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 43169
telemt_desync_full_logged_total 14083
telemt_desync_suppressed_total 29086
telemt_desync_frames_bucket_total{bucket="1_2"} 10507
telemt_desync_frames_bucket_total{bucket="3_10"} 15851
telemt_desync_frames_bucket_total{bucket="gt_10"} 16811
telemt_pool_swap_total 229
telemt_pool_force_close_total 5970
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 75409
telemt_me_writer_removed_unexpected_total 1557
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71240
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69439
telemt_me_writer_teardown_success_total{mode="normal"} 77028
telemt_me_writer_teardown_noop_total 75411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152439
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.130779
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152439
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1438
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10238549
telemt_user_connections_current{user="hello"} 1331
telemt_user_octets_from_client{user="hello"} 197357953416 (183.80 GB)
telemt_user_octets_to_client{user="hello"} 4567258694212 (4.15 TB)
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 206413.7 (57h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11936644
telemt_connections_bad_total 1395220
telemt_connections_current 1253
telemt_connections_me_current 1253
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 321289
telemt_upstream_connect_attempt_total 111277
telemt_upstream_connect_success_total 110323
telemt_upstream_connect_fail_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 111068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 745
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11145
telemt_me_reconnect_success_total 2775
telemt_me_reader_eof_total 2578
telemt_me_idle_close_by_peer_total 2577
telemt_me_seq_mismatch_total 111
telemt_me_route_drop_no_conn_total 5710138
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9194296
telemt_me_endpoint_quarantine_total 1712
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1575
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
telemt_me_writers_active_current 42
telemt_desync_total 43053
telemt_desync_full_logged_total 13783
telemt_desync_suppressed_total 29270
telemt_desync_frames_bucket_total{bucket="1_2"} 11163
telemt_desync_frames_bucket_total{bucket="3_10"} 15889
telemt_desync_frames_bucket_total{bucket="gt_10"} 16001
telemt_pool_swap_total 219
telemt_pool_force_close_total 5710
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 75886
telemt_me_writer_removed_unexpected_total 2615
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7210
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71394
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70176
telemt_me_writer_teardown_success_total{mode="normal"} 78604
telemt_me_writer_teardown_noop_total 75891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 154126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 154445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 154495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 154495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 154495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 154495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 154495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 154495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 154495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 154495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 154495
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.858877
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 154495
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 435
telemt_me_writer_restored_same_endpoint_total 2211
telemt_me_writer_restored_fallback_total 146
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 9198610
telemt_user_connections_current{user="hello"} 1253
telemt_user_octets_from_client{user="hello"} 160028372652 (149.04 GB)
telemt_user_octets_to_client{user="hello"} 3599897352926 (3.27 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 205
```