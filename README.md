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

# Server Metrics 2026-03-23 01:31:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 102295.6 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3543328
telemt_connections_bad_total 316799
telemt_connections_current 859
telemt_connections_me_current 859
telemt_handshake_timeouts_total 110767
telemt_upstream_connect_attempt_total 38055
telemt_upstream_connect_success_total 38054
telemt_upstream_connect_attempts_per_request{bucket="1"} 38054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1405
telemt_me_reconnect_success_total 609
telemt_me_reader_eof_total 626
telemt_me_idle_close_by_peer_total 626
telemt_me_route_drop_no_conn_total 2988014
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2921751
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 799
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 44
telemt_desync_total 12566
telemt_desync_full_logged_total 3950
telemt_desync_suppressed_total 8616
telemt_desync_frames_bucket_total{bucket="1_2"} 3375
telemt_desync_frames_bucket_total{bucket="3_10"} 4577
telemt_desync_frames_bucket_total{bucket="gt_10"} 4614
telemt_pool_swap_total 113
telemt_pool_force_close_total 3482
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 34836
telemt_me_writer_removed_unexpected_total 603
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3426
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31354
telemt_me_writer_teardown_success_total{mode="normal"} 35088
telemt_me_writer_teardown_noop_total 34847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69935
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.697961
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69935
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2910796
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 41581175876 (38.73 GB)
telemt_user_octets_to_client{user="hello"} 797441669600 (742.68 GB)
telemt_user_unique_ips_current{user="hello"} 434
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 115662.1 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4006514
telemt_connections_bad_total 369658
telemt_connections_current 210
telemt_connections_me_current 210
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100828
telemt_upstream_connect_attempt_total 72167
telemt_upstream_connect_success_total 71309
telemt_upstream_connect_fail_total 765
telemt_upstream_connect_attempts_per_request{bucket="1"} 72074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 765
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10139
telemt_me_reconnect_success_total 3636
telemt_me_reader_eof_total 3630
telemt_me_idle_close_by_peer_total 3630
telemt_me_route_drop_no_conn_total 3641550
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3182797
telemt_me_endpoint_quarantine_total 923
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 905
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
telemt_me_writers_active_current 44
telemt_desync_total 12975
telemt_desync_full_logged_total 7277
telemt_desync_suppressed_total 5698
telemt_desync_frames_bucket_total{bucket="1_2"} 2943
telemt_desync_frames_bucket_total{bucket="3_10"} 5090
telemt_desync_frames_bucket_total{bucket="gt_10"} 4942
telemt_pool_swap_total 108
telemt_pool_force_close_total 3095
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 47679
telemt_me_writer_removed_unexpected_total 3559
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6254
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45018
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44584
telemt_me_writer_teardown_success_total{mode="normal"} 51272
telemt_me_writer_teardown_noop_total 47680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98952
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.626865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98952
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 3244
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 3196098
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 43123310399 (40.16 GB)
telemt_user_octets_to_client{user="hello"} 792868997780 (738.42 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 190521.9 (52h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16354186
telemt_connections_bad_total 1656571
telemt_connections_current 897
telemt_connections_me_current 897
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397710
telemt_upstream_connect_attempt_total 85477
telemt_upstream_connect_success_total 85371
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 85388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1719
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3015
telemt_me_reconnect_success_total 1589
telemt_me_reader_eof_total 1537
telemt_me_idle_close_by_peer_total 1535
telemt_me_route_drop_no_conn_total 14047711
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12985063
telemt_me_endpoint_quarantine_total 1270
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1435
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53889
telemt_desync_full_logged_total 17121
telemt_desync_suppressed_total 36768
telemt_desync_frames_bucket_total{bucket="1_2"} 12012
telemt_desync_frames_bucket_total{bucket="3_10"} 21036
telemt_desync_frames_bucket_total{bucket="gt_10"} 20841
telemt_pool_swap_total 206
telemt_pool_force_close_total 6740
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1064
telemt_me_draining_writers_reap_progress_total 64827
telemt_me_writer_removed_unexpected_total 1479
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5527
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60056
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6270
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58087
telemt_me_writer_teardown_success_total{mode="normal"} 65583
telemt_me_writer_teardown_noop_total 64880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130463
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.792794
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130463
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1064
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1376
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12985084
telemt_user_connections_current{user="hello"} 897
telemt_user_octets_from_client{user="hello"} 191219514969 (178.09 GB)
telemt_user_octets_to_client{user="hello"} 3491189113107 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 190523.2 (52h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11892348
telemt_connections_bad_total 1238223
telemt_connections_current 609
telemt_connections_me_current 609
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344636
telemt_upstream_connect_attempt_total 99825
telemt_upstream_connect_success_total 98497
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 99372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4443
telemt_me_reconnect_success_total 1893
telemt_me_reader_eof_total 1760
telemt_me_idle_close_by_peer_total 1760
telemt_me_route_drop_no_conn_total 4557639
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8827287
telemt_me_endpoint_quarantine_total 1274
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1454
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 38889
telemt_desync_full_logged_total 13084
telemt_desync_suppressed_total 25805
telemt_desync_frames_bucket_total{bucket="1_2"} 9635
telemt_desync_frames_bucket_total{bucket="3_10"} 14936
telemt_desync_frames_bucket_total{bucket="gt_10"} 14318
telemt_pool_swap_total 203
telemt_pool_force_close_total 6100
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 63039
telemt_me_writer_removed_unexpected_total 1789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5613
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59072
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5588
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56939
telemt_me_writer_teardown_success_total{mode="normal"} 64685
telemt_me_writer_teardown_noop_total 63064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127749
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.440354
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127749
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1620
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8765044
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 217858745520 (202.90 GB)
telemt_user_octets_to_client{user="hello"} 3965214882351 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 190487.4 (52h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11067038
telemt_connections_bad_total 976387
telemt_connections_current 493
telemt_connections_me_current 493
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345623
telemt_upstream_connect_attempt_total 84104
telemt_upstream_connect_success_total 82545
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 82750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5757
telemt_me_reconnect_success_total 2379
telemt_me_reader_eof_total 2124
telemt_me_idle_close_by_peer_total 2123
telemt_me_route_drop_no_conn_total 5338654
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8364915
telemt_me_endpoint_quarantine_total 1339
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1411
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38192
telemt_desync_full_logged_total 12644
telemt_desync_suppressed_total 25548
telemt_desync_frames_bucket_total{bucket="1_2"} 9645
telemt_desync_frames_bucket_total{bucket="3_10"} 14614
telemt_desync_frames_bucket_total{bucket="gt_10"} 13933
telemt_pool_swap_total 199
telemt_pool_force_close_total 6000
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 741
telemt_me_draining_writers_reap_progress_total 63421
telemt_me_writer_removed_unexpected_total 2274
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6364
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59263
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5429
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57421
telemt_me_writer_teardown_success_total{mode="normal"} 65627
telemt_me_writer_teardown_noop_total 63492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.798872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 741
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2069
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8356870
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 192798213775 (179.56 GB)
telemt_user_octets_to_client{user="hello"} 3472552170501 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 60766.7 (16h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11266826
telemt_connections_bad_total 669222
telemt_connections_current 992
telemt_connections_me_current 992
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 274959
telemt_upstream_connect_attempt_total 58556
telemt_upstream_connect_success_total 55481
telemt_upstream_connect_fail_total 2033
telemt_upstream_connect_attempts_per_request{bucket="1"} 57514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19280
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6017
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2033
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7772
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 792
telemt_me_idle_close_by_peer_total 791
telemt_me_route_drop_no_conn_total 25292924
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9346581
telemt_me_endpoint_quarantine_total 454
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 484
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 16363
telemt_desync_full_logged_total 4468
telemt_desync_suppressed_total 11895
telemt_desync_frames_bucket_total{bucket="1_2"} 3103
telemt_desync_frames_bucket_total{bucket="3_10"} 6666
telemt_desync_frames_bucket_total{bucket="gt_10"} 6594
telemt_pool_swap_total 63
telemt_pool_force_close_total 2042
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 488
telemt_me_draining_writers_reap_progress_total 19137
telemt_me_writer_removed_unexpected_total 1148
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2590
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17639
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17095
telemt_me_writer_teardown_success_total{mode="normal"} 20229
telemt_me_writer_teardown_noop_total 19156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39385
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.908163
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39385
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 488
telemt_me_refill_failed_total 339
telemt_me_writer_restored_same_endpoint_total 809
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 9372447
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 87447777266 (81.44 GB)
telemt_user_octets_to_client{user="hello"} 612959819058 (570.86 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 190493.5 (52h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11012769
telemt_connections_bad_total 956163
telemt_connections_current 685
telemt_connections_me_current 685
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242401
telemt_upstream_connect_attempt_total 112965
telemt_upstream_connect_success_total 111802
telemt_upstream_connect_fail_total 989
telemt_upstream_connect_attempts_per_request{bucket="1"} 112791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 989
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72982
telemt_me_reconnect_success_total 3089
telemt_me_reader_eof_total 2780
telemt_me_idle_close_by_peer_total 2778
telemt_me_route_drop_no_conn_total 5264918
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8685380
telemt_me_endpoint_quarantine_total 1285
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1440
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 46287
telemt_desync_full_logged_total 15864
telemt_desync_suppressed_total 30423
telemt_desync_frames_bucket_total{bucket="1_2"} 9405
telemt_desync_frames_bucket_total{bucket="3_10"} 17718
telemt_desync_frames_bucket_total{bucket="gt_10"} 19164
telemt_pool_swap_total 195
telemt_pool_force_close_total 5712
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67555
telemt_me_writer_removed_unexpected_total 2807
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6881
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63518
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4963
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61843
telemt_me_writer_teardown_success_total{mode="normal"} 70399
telemt_me_writer_teardown_noop_total 67556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137955
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.279337
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137955
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 4302
telemt_me_writer_restored_same_endpoint_total 2605
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8688340
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 194723514269 (181.35 GB)
telemt_user_octets_to_client{user="hello"} 3320790609364 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 127329.7 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11712696
telemt_connections_bad_total 482538
telemt_connections_current 504
telemt_connections_me_current 504
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4762189
telemt_upstream_connect_attempt_total 61402
telemt_upstream_connect_success_total 60953
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 61390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_reconnect_attempts_total 49017
telemt_me_reconnect_success_total 1832
telemt_me_reader_eof_total 1504
telemt_me_idle_close_by_peer_total 1503
telemt_me_route_drop_no_conn_total 4094732
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5628803
telemt_me_endpoint_quarantine_total 865
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 976
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31672
telemt_desync_full_logged_total 10808
telemt_desync_suppressed_total 20864
telemt_desync_frames_bucket_total{bucket="1_2"} 6301
telemt_desync_frames_bucket_total{bucket="3_10"} 12489
telemt_desync_frames_bucket_total{bucket="gt_10"} 12882
telemt_pool_swap_total 135
telemt_pool_force_close_total 3924
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 46890
telemt_me_writer_removed_unexpected_total 1554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3833
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44655
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3483
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42966
telemt_me_writer_teardown_success_total{mode="normal"} 48488
telemt_me_writer_teardown_noop_total 46897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95385
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.706751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95385
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 2741
telemt_me_writer_restored_same_endpoint_total 1621
telemt_me_writer_restored_fallback_total 28
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5620953
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 119962908188 (111.72 GB)
telemt_user_octets_to_client{user="hello"} 2182317597286 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 108300.3 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1531812
telemt_connections_bad_total 36774
telemt_connections_current 427
telemt_connections_me_current 427
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31144
telemt_upstream_connect_attempt_total 51116
telemt_upstream_connect_success_total 50956
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 51088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 791
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2258
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 910
telemt_me_idle_close_by_peer_total 910
telemt_me_route_drop_no_conn_total 519128
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1361588
telemt_me_endpoint_quarantine_total 901
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 896
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 9120
telemt_desync_full_logged_total 2648
telemt_desync_suppressed_total 6472
telemt_desync_frames_bucket_total{bucket="1_2"} 2598
telemt_desync_frames_bucket_total{bucket="3_10"} 3474
telemt_desync_frames_bucket_total{bucket="gt_10"} 3048
telemt_pool_swap_total 117
telemt_pool_force_close_total 2982
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 171
telemt_me_draining_writers_reap_progress_total 43283
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40886
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2894
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40301
telemt_me_writer_teardown_success_total{mode="normal"} 44200
telemt_me_writer_teardown_noop_total 43287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87487
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.340875
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87487
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 171
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 785
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1357395
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 26088374621 (24.30 GB)
telemt_user_octets_to_client{user="hello"} 576915420463 (537.29 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 190498.3 (52h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13336494
telemt_connections_bad_total 1604077
telemt_connections_current 596
telemt_connections_me_current 596
telemt_handshake_timeouts_total 389377
telemt_upstream_connect_attempt_total 75241
telemt_upstream_connect_success_total 74889
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 75105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3004
telemt_me_reconnect_success_total 1502
telemt_me_reader_eof_total 1487
telemt_me_idle_close_by_peer_total 1487
telemt_me_route_drop_no_conn_total 4484286
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10056221
telemt_me_endpoint_quarantine_total 1370
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1442
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
telemt_me_writers_active_current 44
telemt_desync_total 42132
telemt_desync_full_logged_total 13760
telemt_desync_suppressed_total 28372
telemt_desync_frames_bucket_total{bucket="1_2"} 10208
telemt_desync_frames_bucket_total{bucket="3_10"} 15482
telemt_desync_frames_bucket_total{bucket="gt_10"} 16442
telemt_pool_swap_total 211
telemt_pool_force_close_total 5611
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 679
telemt_me_draining_writers_reap_progress_total 68016
telemt_me_writer_removed_unexpected_total 1425
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5350
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64143
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5437
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62405
telemt_me_writer_teardown_success_total{mode="normal"} 69493
telemt_me_writer_teardown_noop_total 68018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137511
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.794590
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137511
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 679
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 1319
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 10022924
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 194840293804 (181.46 GB)
telemt_user_octets_to_client{user="hello"} 4442085493200 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 190494.8 (52h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11654533
telemt_connections_bad_total 1363003
telemt_connections_current 637
telemt_connections_me_current 637
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311803
telemt_upstream_connect_attempt_total 102697
telemt_upstream_connect_success_total 101808
telemt_upstream_connect_fail_total 681
telemt_upstream_connect_attempts_per_request{bucket="1"} 102489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 681
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10483
telemt_me_reconnect_success_total 2590
telemt_me_reader_eof_total 2401
telemt_me_idle_close_by_peer_total 2400
telemt_me_seq_mismatch_total 99
telemt_me_route_drop_no_conn_total 5651680
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8967535
telemt_me_endpoint_quarantine_total 1547
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1444
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
telemt_me_writers_active_current 46
telemt_desync_total 41821
telemt_desync_full_logged_total 13463
telemt_desync_suppressed_total 28358
telemt_desync_frames_bucket_total{bucket="1_2"} 10804
telemt_desync_frames_bucket_total{bucket="3_10"} 15382
telemt_desync_frames_bucket_total{bucket="gt_10"} 15635
telemt_pool_swap_total 201
telemt_pool_force_close_total 5387
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 68044
telemt_me_writer_removed_unexpected_total 2444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6700
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63873
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62657
telemt_me_writer_teardown_success_total{mode="normal"} 70573
telemt_me_writer_teardown_noop_total 68049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138622
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.479399
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138622
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2084
telemt_me_writer_restored_fallback_total 134
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8972120
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 157437720812 (146.63 GB)
telemt_user_octets_to_client{user="hello"} 3492094989334 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 61
```